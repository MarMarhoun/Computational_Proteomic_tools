# Computational proteomics tools
# Introduction

Metaproteomics is the study of the proteins expressed in a cell, organism, or tissue. This includes protein identification and quantification (or quantitation), protein–protein interactions, protein complexes prediction, protein modifications and protein localization in the cell. Metaproteomics mostly utilizes methods originating from mass spectrometry (MS)-based proteomics. Mass spectrometry is a high performance instrument for molecular analysis, evidenced in part by the increasing number of biologists utilizing MS for protein identification, quantification, and characterization. Furthermore, Computational Proteomics is about the computational methods, algorithms, databases and methodologies used to process, manage, analyze and interpret the data produced in proteomics experiments. The broad application of proteomics in different biological and medical fields, as well as the diffusion of high-throughput platforms, leads to increasing volumes of available proteomics data requiring efficient algorithms, new data management capabilities and novel analysis, inference and visualization techniques. 

In the proteomics community, most of the tools start to use Python widely used around 2012 when several mature Python packages were published including pymzML, Pyteomics and pyOpenMS. This has led to an ever-increasing interest in the Python programming language in the proteomics and mass spectrometry community. The number of publications referencing or using Python has risen eight fold since 2012 (compared with the same time period before 2012), with multiple open-source Python packages now supporting mass spectrometric data analysis and processing. Computing and data analysis in mass spectrometry is very diverse and in many cases must be tailored to a specific experiment. Often, multiple analysis steps have to be performed (identification, quantification, post-translational modification analysis, filtering, FDR analysis etc.) in an analysis pipeline, which requires high flexibility in the analysis. This is where Python truly shines, due to its flexibility, visualization capabilities and the ability to extend computation with a large number of powerful libraries. Python can be used to quickly prototype software, combine existing libraries into powerful analysis workflows while avoiding the trap of re-inventing the wheel for a new project.

Here in this repository, you will find useful tools for processing, analysis, and identification and also visualization proteomics data.

> __PS:__ If there are others tools, please contact me and send them to me in private to add them.

# Packages and repositories 

<a name="PyProteomics"></a>
### PyProteomics

[PyProteomics](https://github.com/jfnavarro/proteomics) is the name of a repository which contains a bunch of tools and scripts for processing, analysis and visualization of proteomics data (more precisely mass spectrometry data) using python language programming. 

* Link: https://github.com/jfnavarro/proteomics


<a name="PythonProteomics"></a>
### PythonProteomics

[PythonProteomics](https://pyteomics.readthedocs.io/en/latest/) : This repository contains a list of open source Python tools for Proteomics analysis. 

* Link: https://github.com/Roestlab/PythonProteomics

<a name="ThermoRawFileParser"></a>
### ThermoRawFileParser
[ThermoRawFileParser](https://github.com/compomics/ThermoRawFileParser) Thermo RAW file parser that runs on Linux with mono. Wrapper around the .net (C#) ThermoFisher ThermoRawFileReader library for running on Linux with mono (works on Windows too). It takes a thermo RAW file as input and outputs a metadata file and the spectra in 3 possible formats: <br>
    - MGF: MS2 and MS3 spectra <br>
    - mzML and indexed mzML: MS1, MS2 and MS3 spectra <br>
    - Apache Parquet: under development

* Code: https://github.com/compomics/ThermoRawFileParser
* Publication: https://pubmed.ncbi.nlm.nih.gov/31755270/

<a name="PAW_pipeline"></a>
### PAW_pipeline 

[PAW_pipeline](https://github.com/pwilmart/PAW_pipeline): The PAW pipeline consists of open source Python scripts to process Thermo mass spectrometer RAW files in a best-practices shotgun proteomics analysis pipeline.

* Code: https://github.com/pwilmart/PAW_pipeline


<a name="MSFragger"></a>
### MSFragger

[MSFragger](https://github.com/Nesvilab/MSFragger): Ultra fast and comprehensive peptide identification in mass spectrometry–based proteomics. MSFragger is an ultrafast database search tool for peptide identification in mass spectrometry-based proteomics. It has demonstrated excellent performance across a wide range of datasets and applications. MSFragger is suitable for standard shotgun proteomics analyses as well as large datasets (including timsTOF PASEF data), enzyme unconstrained searches (e.g. peptidome), ‘open’ database searches (i.e. precursor mass tolerance set to hundreds of Daltons) for identification of modified peptides, and glycopeptide identification (N-Codeed and O-Codeed) with MSFragger Glyco mode.

* Code: https://github.com/Nesvilab/MSFragger
* Publication: https://www.nature.com/articles/nmeth.4256

<a name="SearchGUI"></a>
### SearchGUI

[SearchGUI](https://github.com/compomics/searchgui): is a highly adaptable open-source common interface for configuring and running proteomics search and de novo engines, currently supporting X! Tandem, MyriMatch, MS Amanda, MS-GF+, OMSSA, Comet, Tide, Andromeda, MetaMorpheus, Novor and DirecTag.

* Code: https://github.com/compomics/searchgui
* Publication: https://pubmed.ncbi.nlm.nih.gov/29774740/

<a name="Denovogui"></a>
### Denovogui

[Denovogui](https://github.com/compomics/denovogui): is graphical user interface for de novo sequencing of tandem mass spectra. DeNovoGUI provides a user-friendly open-source graphical user interface for running the de novo sequencing algorithms Novor, DirecTag, PepNovo+ and pNovo+ (beta) on Windows, Mac and Linux.

* Code: https://github.com/compomics/denovogui
* Publication: https://pubmed.ncbi.nlm.nih.gov/24295440/

<a name="Dnmso"></a>
### Dnmso
[Dnmso](https://github.com/savastakan/dnmso) is an Ontology for Representing De Novo Sequencing Results from Tandem-MS Data. De Novo MS Ontology (DNMSO) can provide many-to-many mappings between spectra and peptides. In addition to this and many other improvements over DNML, an all-encompassing application programming interface which supports any file operation necessary for de novo sequencing from spectra input to reading, writing, creating, of the DNMSO format as well as conversion from existing formats. This essentially removes all overhead from the production of de novo sequencing tools and allows developers to completely concentrate on algorithm development.

* Code:  https://github.com/savastakan/dnmso
* Publication: https://pubmed.ncbi.nlm.nih.gov/33150092/

<a name="Ursgal"></a>
### Ursgal

[Ursgal]( https://github.com/ursgal/ursgal): is a Python module that offers a generalized interface to common bottom-up proteomics tools for Large-Scale Analysis, e.g.: <br>

       1. Peptide spectrum matching with up to eight different search engines (some available in multiple versions), including four open modification search engines <br>
       2. Evaluation and post processing of search results with up to two different engines for protein database searches as well as two engines for the post processing of mass difference results from open modification engines <br>
       3. Integration of search results from different search engines <br>
       4. De novo sequencing with up to four different search engines <br>
       5. Miscellaneous tools including the creation of a target decoy database as well as filtering, sanitizing and visualizing of results.

* Code: https://github.com/ursgal/ursgal
* Publication: https://github.com/ursgal/ursgal

<a name="py-pgatk"></a>
### py-pgatk

[py-pgatk](https://github.com/bigbio/py-pgatk): is a Python library part of the ProteoGenomics Analysis Toolkit. It provides different bioinformatics tools for proteogenomics data analysis.

* Code: https://github.com/bigbio/py-pgatk
* Documentation: https://pgatk.readthedocs.io/en/latest/pypgatk.html

<a name="Peptide-shaker"></a>
### Peptide-shaker

[Peptide-shaker](https://github.com/compomics/peptide-shaker): is a search engine independent platform for interpretation of proteomics identification results from multiple search and de novo engines, currently supporting X!Tandem, MS-GF+, MS Amanda, OMSSA, MyriMatch, Comet, Tide, Mascot, Andromeda, MetaMorpheus, Novor, DirecTag and mzIdentML. PeptideShaker aggregates the results in a single identification set, annotates spectra, computes a consensus score, maps sequences and performs protein inference, scores post-translational modification localization, runs statistical validation, quality control, and annotates the results using multiple sources of information like Gene Ontology, UniProt and Ensemble annotation, and protein structures.

* Code: https://github.com/compomics/peptide-shaker
* Publication: https://www.nature.com/articles/nbt.3109

<a name="PyQms"></a>
### PyQms

[PyQms](https://github.com/pyQms/pyqms): is an open-source software for accurate quantification of all types of molecules measurable by MS. pyQms uses isotope pattern matching which offers accurate quality assessment of the quantification and the ability to directly incorporate mass spectrometer accuracy. pyQms is an extension to Python that offers amongst other things: <br>

      1. fast and accurate quantification of all high-res LC-MS data <br>
      2. full labeling and modification flexibility <br>
      3. full platform independence

* Code: https://github.com/pyQms/pyqms
* Publication: https://pubmed.ncbi.nlm.nih.gov/28729385/

<a name="qPLEXanalyzer"></a>
### qPLEXanalyzer

[PyQms](https://github.com/pyQms/pyqms): is an R package for statistical analysis of qPLEX-RIME proteomics data. It can also be used for isobaric labelling based proteome analysis. The major functionalities includes import of quantitative proteomics datasets, visualizing quality control statistics, data normalization and differential statistics analysis.

* Code: https://github.com/crukci-bioinformatics/Proteomics_package
