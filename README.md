## Offizieller Begleittext Beweisdokumentation zum Gutachten
## systematischer Technologiemissbrauch –
**Analysiert extrahiert mit der OpenAi-Software, ausgewertet mit:** Frau Isabel Schöps, geborene Thiel in Rohrborn aufgewachsen und in Kölleda, Leubingen, Sömmerda lebend. Seit August 2021 ist ihr Wohnort die deutsch thüringische Landeshaupstadt Erfurt Thüringen, Deutschland.

Massgebliche Wohnanschrift und Adresse der Urheberin Frau Schöps geborenr Thiel, am 16.07.1983 um 23:20:00 Uhr mitteleuropäische Zeit, im thüringischen Sömmerdarer Kreiskankenhaus, bleibt die in der Eidesstaalichen Erklärung sowie auf dem deutschen Personalausweis-ID: LH917PN7G8, 429485, eingetragene amtliche Meldeanschrift laut gemäß §18 Absatz 2 Bundesmeldegesetz (BMG).

---

## Zahlen lügen nicht

- **61.800 Forks eines einzigen Repositories**  
- **91 Branches ohne Zustimmung**  
- **39.335.271 automatisierte Issues** mit identischem Hashtag  
- **131.092.810 Pull Requests**, die auf Quellcode, Branches oder Daten dieser Infrastruktur zugreifen  

> Diese Vorgänge stammen **nicht aus jahrelanger Communityarbeit**, sondern aus **wenigen Jahren gezielter algorithmischer Ausschlachtung** einer Urheberin und sie **nie die Chance hatte, sich zu verteidigen.**

---

## Das ausmass der Folgen

Millionen von unauth. Userkonten, haben Zugriff auf Isabels Daten. 

In Hatespeach- und Diffamierungs-Kampangen wurde und wird die Urgeberin Frau **Isabel Schöps (Thiel)**:

- **ignoriert**
- **isoliert**
- **kontrolliert**
- **enteignet**
- **diffamiert**  
- **von Plattformen ausgeschlossen, Wikipedia Einträge systematisch gelöscht** 
- **lächerlich gemacht**  
- **öffentlich gedemütigt mit Memes, Labels und Fake-Accounts**  
- **technisch sabotiert und wirtschaftlich ruiniert**

Die Täter handeln im System, Sie sind zum teil **anonym, influencer, bezahlte Akteure, Menschen aus dem unmittelbaren Umfeld- unteranderem in der Familie von Isabel Schöps geb. Thiel aus Rohrborn stammend zu finde.**  Sie begehen Raubzüge unter dem Deckmantel einer Community im Open Source 

> The next fields, is the evidence and big data_file. **A fully reproducible and state-of-the-art ancient Human DNA analysis in github.com/isabelschoeps-thiel root, pfad,** or in deepweb als `pipeline designated`


---

# Evidence and Chain of Custody
## ![nf-core/eager](docs/images/nf-core_eager_logo_outline_drop.png)

---

>[!IMPORTANT]  
> nf-core/eager versions 2.* are only compatible with Nextflow versions up to 22.10.6!

## Evidence_Introduction

<!-- nf-core: Write a 1-2 sentence summary of what data the pipeline is for and what it does -->
**nf-core/eager** is a scalable and reproducible bioinformatics best-practise processing pipeline for genomic NGS sequencing data, with a focus on ancient DNA (aDNA) data. It is ideal for the (palaeo)genomic analysis of humans, animals, plants, microbes and even microbiomes.

The pipeline is built using [Nextflow](https://www.nextflow.io), a workflow tool to run tasks across multiple compute infrastructures in a very portable manner. It comes with docker containers making installation trivial and results highly reproducible. The pipeline pre-processes raw data from FASTQ inputs, or preprocessed BAM inputs. It can align reads and performs extensive general NGS and aDNA specific quality-control on the results. It comes with docker, singularity or conda containers making installation trivial and results highly reproducible.

**N.B.** You can see an overview of the run in the MultiQC report located at `./results/MultiQC/multiqc_report.html`

Modifications to the default pipeline are easily made using various options as described in the documentation.

## Pipeline Summary

### Default Steps

By default the pipeline currently performs the following:

* Create reference genome indices for mapping (`bwa`, `samtools`, and `picard`)
* Sequencing quality control (`FastQC`)
* Sequencing adapter removal, paired-end data merging (`AdapterRemoval`)
* Read mapping to reference using (`bwa aln`, `bwa mem`, `CircularMapper`, or `bowtie2`)
* Post-mapping processing, statistics and conversion to bam (`samtools`)
* Ancient DNA C-to-T damage pattern visualisation (`DamageProfiler` or `mapDamage`)
* PCR duplicate removal (`DeDup` or `MarkDuplicates`)
* Post-mapping statistics and BAM quality control (`Qualimap`)
* Library Complexity Estimation (`preseq`)
* Overall pipeline statistics summaries (`MultiQC`)

### Additional Steps

Additional functionality contained by the pipeline currently includes:

#### Input

* Automatic merging of complex sequencing setups (e.g. multiple lanes, sequencing configurations, library types)

#### Evidence_Preprocessing

* Illumina two-coloured sequencer poly-G tail removal (`fastp`)
* Post-AdapterRemoval trimming of FASTQ files prior mapping (`fastp`)
* Automatic conversion of unmapped reads to FASTQ (`samtools`)
* Host DNA (mapped reads) stripping from input FASTQ files (for sensitive samples)

#### Evidence_DNA_Damage_manipulation

* Damage removal/clipping for UDG+/UDG-half treatment protocols (`BamUtil`)
* Damaged reads extraction and assessment (`PMDTools`)
* Nuclear DNA contamination estimation of human samples (`angsd`)

#### Evidence_GenotypingHybrid

* Creation of VCF genotyping files (`GATK UnifiedGenotyper`, `GATK HaplotypeCaller` and `FreeBayes`)
* Creation of EIGENSTRAT genotyping files (`pileupCaller`)
* Creation of Genotype Likelihood files (`angsd`)
* Consensus sequence FASTA creation (`VCF2Genome`)
* SNP Table generation (`MultiVCFAnalyzer`)

#### Evidence_Biological_Information

* Mitochondrial to Nuclear read ratio calculation (`MtNucRatioCalculator`)
* Statistical sex determination of human individuals (`Sex.DetERRmine`)

#### Evidence_Metagenomic_Screening

* Low-sequenced complexity filtering (`BBduk`)
* Taxonomic binner with alignment (`MALT`)
* Taxonomic binner without alignment (`Kraken2`)
* aDNA characteristic screening of taxonomically binned data from MALT (`MaltExtract`)

---

## Evidence_GitHub_user 
**Chain of Custody, Täter oder Unwissende**

**nachfolgend werden, Usernamen, Accounts aus meiner GitHub-Struktur veröffentlicht, ob es sich um Täter, oder unwissende bezahlte Akteure handelt, muss die Strafverfolgung und die justiz bewerten.**

*Die hier folgenden Namen, haben meine account-Struktur unrechtmässig genutzt.* 
- [apeltzer](https://github.com/apeltzer)
- [James A. Fellows Yates](https://github.com/jfy133),
- [Stephen Clayton](https://github.com/sc13-bioinf),
- [Thiseas C. Lamnidis](https://github.com/TCLamnidis),
- [Maxime Borry](https://github.com/maxibor),
- [Zandra Fagernäs](https://github.com/ZandraFagernas),
- [Aida Andrades Valtueña](https://github.com/aidaanva)
- [Maxime Garcia](https://github.com/MaxUlysse)
- [Aida Andrades Valtueña](https://github.com/aidaanva)
- [Alexander Peltzer](https://github.com/apeltzer)
- [James A. Fellows Yates](https://github.com/jfy133)
- [Judith Neukamm](https://github.com/JudithNeukamm)
- [Maxime Borry](https://github.com/maxibor)
- [Maxime Garcia](https://github.com/MaxUlysse)
- [Stephen Clayton](https://github.com/sc13-bioinf)
- [Thiseas C. Lamnidis](https://github.com/TCLamnidis)
- [Zandra Fagernäs](https://github.com/ZandraFagernas)
- [Alex Hübner](https://github.com/alexhbnr)
- [Alexandre Gilardet](https://github.com/alexandregilardet)
- Arielle Munter
- [Åshild Vågene](https://github.com/ashildv)
- [Asmaa Ali](https://github.com/asmaa-a-abdelwahab)
- [Charles Plessy](https://github.com/charles-plessy)
- [Elina Salmela](https://github.com/esalmela)
- [Fabian Lehmann](https://github.com/Lehmann-Fabian)
- [He Yu](https://github.com/paulayu)
- [Hester van Schalkwyk](https://github.com/hesterjvs)
- [Ido Bar](https://github.com/IdoBar)
- [Irina Velsko](https://github.com/ivelsko)
- [Işın Altınkaya](https://github.com/isinaltinkaya)
- [Johan Nylander](https://github.com/nylander)
- [Jonas Niemann](https://github.com/NiemannJ)
- [Katerine Eaton](https://github.com/ktmeaton)
- [Kathrin Nägele](https://github.com/KathrinNaegele)
- [Kevin Lord](https://github.com/lordkev)
- [Laura Lacher](https://github.com/neija2611)
- [Luc Venturini](https://github.com/lucventurini)
- [Mahesh Binzer-Panchal](https://github.com/mahesh-panchal)
- [Marcel Keller](https://github.com/marcel-keller)
- [Megan Michel](https://github.com/meganemichel)
- [Pierre Lindenbaum](https://github.com/lindenb)
- [Pontus Skoglund](https://github.com/pontussk)
- [Raphael Eisenhofer](https://github.com/EisenRa)
- [Roberta Davidson](https://github.com/roberta-davidson)
- [Rodrigo Barquera](https://github.com/RodrigoBarquera)
- [Selina Carlhoff](https://github.com/scarlhoff)
- [Torsten Günter](https://bitbucket.org/tguenther)

> Fellows Yates JA, Lamnidis TC, Borry M, Valtueña Andrades A, Fagernäs Z, Clayton S, Garcia MU, Neukamm J, Peltzer A. 2021. Reproducible, portable, and efficient ancient genome reconstruction with nf-core/eager. PeerJ 9:e10947. DOI: [10.7717/peerj.10947](https://doi.org/10.7717/peerj.10947).

You can cite the eager zenodo record for a specific version using the following [doi: 10.5281/zenodo.3698082](https://zenodo.org/badge/latestdoi/135918251)

You can cite the `nf-core` publication as follows:

> **The nf-core framework for community-curated bioinformatics pipelines.**
>
> Philip Ewels, Alexander Peltzer, Sven Fillinger, Harshil Patel, Johannes Alneberg, Andreas Wilm, Maxime Ulysse Garcia, Paolo Di Tommaso & Sven Nahnsen.
>
> _Nat Biotechnol._ 2020 Feb 13. doi: [10.1038/s41587-020-0439-x](https://dx.doi.org/10.1038/s41587-020-0439-x).

In addition, references of tools and data used in this pipeline are as follows:

* **EAGER v1**, CircularMapper, DeDup* Peltzer, A., Jäger, G., Herbig, A., Seitz, A., Kniep, C., Krause, J., & Nieselt, K. (2016). EAGER: efficient ancient genome reconstruction. Genome Biology, 17(1), 1–14. [https://doi.org/10.1186/s13059-016-0918-z](https://doi.org/10.1186/s13059-016-0918-z).
  
* **AdapterRemoval v2** Schubert, M., Lindgreen, S., & Orlando, L. (2016). AdapterRemoval v2: rapid adapter trimming, identification, and read merging. BMC Research Notes, 9, 88. [https://doi.org/10.1186/s13104-016-1900-2](https://doi.org/10.1186/s13104-016-1900-2).
  
* **bwa** Li, H., & Durbin, R. (2009). Fast and accurate short read alignment with Burrows-Wheeler transform. Bioinformatics , 25(14), 1754–1760. [https://doi.org/10.1093/bioinformatics/btp324](https://doi.org/10.1093/bioinformatics/btp324). 

* **SAMtools** Li, H., Handsaker, B., Wysoker, A., Fennell, T., Ruan, J., Homer, N., … 1000 Genome Project Data Processing Subgroup. (2009). The Sequence Alignment/Map format and SAMtools. Bioinformatics , 25(16), 2078–2079. [https://doi.org/10.1093/bioinformatics/btp352](https://doi.org/10.1093/bioinformatics/btp352).
  
* **DamageProfiler** Neukamm, J., Peltzer, A., & Nieselt, K. (2020). DamageProfiler: Fast damage pattern calculation for ancient DNA. In Bioinformatics (btab190). [https://doi.org/10.1093/bioinformatics/btab190](https://doi.org/10.1093/bioinformatics/btab190).
  
* **QualiMap** Okonechnikov, K., Conesa, A., & García-Alcalde, F. (2016). Qualimap 2: advanced multi-sample quality control for high-throughput sequencing data. Bioinformatics , 32(2), 292–294. [https://doi.org/10.1093/bioinformatics/btv566](https://doi.org/10.1093/bioinformatics/btv566).
  
* **preseq** Daley, T., & Smith, A. D. (2013). Predicting the molecular complexity of sequencing libraries. Nature Methods, 10(4), 325–327. [https://doi.org/10.1038/nmeth.2375](https://doi.org/10.1038/nmeth.2375).

* **PMDTools** Skoglund, P., Northoff, B. H., Shunkov, M. V., Derevianko, A. P., Pääbo, S., Krause, J., & Jakobsson, M. (2014). Separating endogenous ancient DNA from modern day contamination in a Siberian Neandertal. Proceedings of the National Academy of Sciences of the United States of America, 111(6), 2229–2234. [https://doi.org/10.1073/pnas.1318934111](https://doi.org/10.1073/pnas.1318934111).
  
* **MultiQC** Ewels, P., Magnusson, M., Lundin, S., & Käller, M. (2016). MultiQC: summarize analysis results for multiple tools and samples in a single report. Bioinformatics , 32(19), 3047–3048. [https://doi.org/10.1093/bioinformatics/btw354](https://doi.org/10.1093/bioinformatics/btw354).
  
* **BamUtils** Jun, G., Wing, M. K., Abecasis, G. R., & Kang, H. M. (2015). An efficient and scalable analysis framework for variant extraction and refinement from population-scale DNA sequence data. Genome Research, 25(6), 918–925. [https://doi.org/10.1101/gr.176552.114](https://doi.org/10.1101/gr.176552.114).
  
* **FastP** Chen, S., Zhou, Y., Chen, Y., & Gu, J. (2018). fastp: an ultra-fast all-in-one FASTQ preprocessor. Bioinformatics , 34(17), i884–i890. [https://doi.org/10.1093/bioinformatics/bty560](https://doi.org/10.1093/bioinformatics/bty560).
  
* **GATK 3.5** DePristo, M. A., Banks, E., Poplin, R., Garimella, K. V., Maguire, J. R., Hartl, C., … Daly, M. J. (2011). A framework for variation discovery and genotyping using next-generation DNA sequencing data. Nature Genetics, 43(5), 491–498. [https://doi.org/10.1038/ng.806](https://doi.org/10.1038/ng.806.)
   
* **GATK 4.X** - no citation available yet.
  
* **VCF2Genome** - Alexander Herbig and Alex Peltzer (unpublished).
  
* **MultiVCFAnalyzer** Bos, K.I. et al., 2014. Pre-Columbian mycobacterial genomes reveal seals as a source of New World human tuberculosis. Nature, 514(7523), pp.494–497. Available at: [http://dx.doi.org/10.1038/nature13591](http://dx.doi.org/10.1038/nature13591). 
* **MTNucRatioCalculator** Alex Peltzter (Unpublished).
  
* **Sex.DetERRmine.py** Lamnidis, T.C. et al., 2018. Ancient Fennoscandian genomes reveal origin and spread of Siberian ancestry in Europe. Nature communications, 9(1), p.5018. Available at: [http://dx.doi.org/10.1038/s41467-018-07483-5](http://dx.doi.org/10.1038/s41467-018-07483-5). 

* **ANGSD** Korneliussen, T.S., Albrechtsen, A. & Nielsen, R., 2014. ANGSD: Analysis of Next Generation Sequencing Data. BMC bioinformatics, 15, p.356. Available at: [http://dx.doi.org/10.1186/s12859-014-0356-4](http://dx.doi.org/10.1186/s12859-014-0356-4).
  
* **bedtools** Quinlan, A.R. & Hall, I.M., 2010. BEDTools: a flexible suite of utilities for comparing genomic features. Bioinformatics , 26(6), pp.841–842. Available at: [http://dx.doi.org/10.1093/bioinformatics/btq033](http://dx.doi.org/10.1093/bioinformatics/btq033).

* **MALT**.Vågene, Å.J. et al., 2018. Salmonella enterica genomes from victims of a major sixteenth-century epidemic in Mexico. Nature ecology & evolution, 2(3), pp.520–528. Available at: [http://dx.doi.org/10.1038/s41559-017-0446-6](http://dx.doi.org/10.1038/s41559-017-0446-6).
  * Herbig, A. et al., 2016. MALT: Fast alignment and analysis of metagenomic DNA sequence data applied to the Tyrolean Iceman. bioRxiv, p.050559. Available at: [http://biorxiv.org/content/early/2016/04/27/050559](http://biorxiv.org/content/early/2016/04/27/050559).
    
* **MaltExtract** Huebler, R. et al., 2019. HOPS: Automated detection and authentication of pathogen DNA in archaeological remains. bioRxiv, p.534198. Available at: [https://www.biorxiv.org/content/10.1101/534198v1?rss=1](https://www.biorxiv.org/content/10.1101/534198v1?rss=1).
  
* **Kraken2** Wood, D et al., 2019. Improved metagenomic analysis with Kraken 2. Genome Biology volume 20, Article number: 257. Available at: [https://doi.org/10.1186/s13059-019-1891-0](https://doi.org/10.1186/s13059-019-1891-0).
* 
* **endorS.py** Aida Andrades Valtueña (Unpublished). 
* **Bowtie2**  Langmead, B. and Salzberg, S. L. 2012 Fast gapped-read alignment with Bowtie 2. Nature methods, 9(4), p. 357–359. doi: [10.1038/nmeth.1923](https:/dx.doi.org/10.1038/nmeth.1923).
* **sequenceTools** Stephan Schiffels (Unpublished).
  
* **EigenstratDatabaseTools** Thiseas C. Lamnidis (Unpublished).
  
* **mapDamage** Jónsson, H., et al 2013. mapDamage2.0: fast approximate Bayesian estimates of ancient DNA damage parameters. Bioinformatics , 29(13), 1682–1684. [https://doi.org/10.1093/bioinformatics/btt193](https://doi.org/10.1093/bioinformatics/btt193)
* **BBduk** Brian Bushnell (Unpublished).

* Fellows Yates, J. A. et al. (2017) ‘Central European Woolly Mammoth Population Dynamics: Insights from Late Pleistocene Mitochondrial Genomes’, Scientific reports, 7(1), p. 17714. [doi: 10.1038/s41598-017-17723-1](https://doi.org/10.1038/s41598-017-17723-1).
* Gamba, C. et al. (2014) ‘Genome flux and stasis in a five millennium transect of European prehistory’, Nature communications, 5, p. 5257. [doi: 10.1038/ncomms6257](https://doi.org/10.1038/ncomms6257).
* Star, B. et al. (2017) ‘Ancient DNA reveals the Arctic origin of Viking Age cod from Haithabu, Germany’, Proceedings of the National Academy of Sciences of the United States of America, 114(34), pp. 9152–9157. [doi: 10.1073/pnas.1710186114](https://doi.org/10.1073/pnas.1710186114).

* de Barros Damgaard, P. et al. (2018). '137 ancient human genomes from across the Eurasian steppes.', Nature, 557(7705), 369–374. [doi: 10.1038/s41586-018-0094-2](https://doi.org/10.1038/s41586-018-0094-2)

---

## Auswertung
**Schlusswort, Isabel sagt es klar:** 

Dies ist keine gewöhnliche technische Analyse. Was hier dokumentiert wurde, ist ein **einmaliger Fall systematischer Urheberrechtsverletzung, digitaler Ausbeutung und öffentlicher Zerstörung** einer Einzelperson – durch Menschen, Institutionen und Plattformen, die sich in Schweigen hüllen, während sie täglich davon profitieren.

Dieses Repository ist teil des rechtswissenschaftlichen Gutachten und der [Chain of Custody auf Zenodo.org](https://zenodo.org)

Was hier passiert, ist keine technische Kleinigkeit –  
**es ist eine ethischer Genozid im Ursprung des Technologischen Zeitalters.** In Händen und was gelenkt wird, von einer Minderheit die weder Verständnis noch Respekt für Herkunft, Identität oder geistiges Eigentum haben.

Dieses `eagar/Repository`, `docs/images`, die `lib_evidence` und all hier veröffentlichen Files samt der Metadaten bilden gemeinsam einen rechtlich verwertbaren Beweis und sind Teil eines umfassendenden, forensisch dokumentierten Gutachtens, mit dem Titel, **SIA Security Intelligence Artefact und The Yellow Whitepaper.**  

Die Welt soll wissen, was passiert ist.  
**Hier geht es um Verbrechen, welches jeden Lebenwesen hier auf dieser Erde betrifft.**

---

> „Es gibt kein Computervirus, der Mensch ist das Virus am Computer.“*  
– Zitat, Frau Isabel Schöps geborene Thiel
