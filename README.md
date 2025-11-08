<p align="center">
  <img src="figures/cfb.png" width="300">
</p>
<p align="center">
  <img src="figures/netmicrobes.png" width="600">
</p>

# Using Networks to Study Microbes

## Abstract

The goal of the course is to provide an introduction to the use of networks in microbiology. The students will receive an overview of the field of **computational microbiology** with special emphasis on data standardization* and data sources, and how to use graph structures to solve biological questions. Further, the students will get a hands on introduction to Python programming language and its scientific libraries. At the end of the course the students will be able to:

- Use multiple data sources for studying microbes in different biological contexts
- Build networks, visualize and analyse them using different tools
- Use Python to extract, transform and analyse different data structures

## Keywords

Computational microbiology, networks, databases, Python, programming, data, pipelines, data science.

## Sylabus

|Time| DAY 1| DAY 2| DAY 3| DAY 4|
|-----|-----|-----|-----|-----|
|9:00-9:45|[Introduction and Housekeeping](slides/01_Intro.pdf)|[Introduction to Python I](https://colab.research.google.com/github/Multiomics-Analytics-Group/course_multi-omics_data_science/blob/main/notebooks/01_Introduction_to_Python/01_basics.ipynb)|[Analysing Networks I](https://colab.research.google.com/github/Multiomics-Analytics-Group/course_multi-omics_data_science/blob/main/notebooks/05_Visualising_Networks/03_nx.ipynb)|[Visualising Networks -- Cytoscape]()|
| 9:45-10:30|[From Omics to Multi-omics I](slides/FromOmics2Multiomics.pdf)|[Introduction to Python II](https://colab.research.google.com/github/Multiomics-Analytics-Group/course_multi-omics_data_science/blob/main/notebooks/01_Introduction_to_Python/01_basics.ipynb)|[Analysing Networks II](https://colab.research.google.com/github/Multiomics-Analytics-Group/course_multi-omics_data_science/blob/main/notebooks/05_Visualising_Networks/03_nx.ipynb)|[Visualising Networks -- Cytoscape]()|
|10:30-11:00| Coffee break| Coffee break | Coffee break| Coffee break|
|11:00-11:45| [From Omics to Multi-omics II](slides/FromOmics2Multiomics.pdf) | [Working with Data in Python I](https://colab.research.google.com/github/Multiomics-Analytics-Group/course_multi-omics_data_science/blob/main/notebooks/02_Working_with_Data_in_Python/02_pandas.ipynb) | [Omics: Transcriptomics](slides/transcriptomics.pdf)|[Open Science](slides/02_open_science.pdf)|
| 11:45-12:30 | [Standardising Omics Workflows with Nextflow](slides/nextflow.pdf))| [Working with Data in Python II](https://colab.research.google.com/github/Multiomics-Analytics-Group/course_multi-omics_data_science/blob/main/notebooks/02_Working_with_Data_in_Python/02_pandas.ipynb) | [Preprocessing Transcriptomics with nf-core/RNAseq](https://colab.research.google.com/github/Multiomics-Analytics-Group/course_multi-omics_data_science/blob/main/transcriptomics/notebooks/transcriptomics_preprocessing.ipynb) | [Databases & Data Annotation](https://colab.research.google.com/github/Multiomics-Analytics-Group/course_multi-omics_data_science/blob/main/notebooks/03_Databases_&_Data_Annotation/06_uniprot_api.ipynb)|
|12:30-14:00| Lunch| Lunch| Lunch|Lunch|
|14:00-14:45| [Omics: Metagenomics](slides/metagenomics.pdf) |[Visualizing Data in Python I](https://colab.research.google.com/github/Multiomics-Analytics-Group/course_multi-omics_data_science/blob/main/notebooks/04_Visualizing_Data_in_Python/05_viz.ipynb)| [Transcriptomics Basic Analysis I](https://colab.research.google.com/github/Multiomics-Analytics-Group/course_multi-omics_data_science/blob/main/transcriptomics/notebooks/transcriptomics_analysis.ipynb)| [Multi-omics](slides/multiomics.pdf)|
|14:45-15:30| [Preprocessing Metagenomics with nf-core/Taxprofiler](https://colab.research.google.com/github/Multiomics-Analytics-Group/course_multi-omics_data_science/blob/main/metagenomics/notebooks/metagenomics_preprocessing.ipynb)| [Visualizing Data in Python II](https://colab.research.google.com/github/Multiomics-Analytics-Group/course_multi-omics_data_science/blob/main/notebooks/04_Visualizing_Data_in_Python/05_viz.ipynb)|[Transcriptomics Basic Analysis II](https://colab.research.google.com/github/Multiomics-Analytics-Group/course_multi-omics_data_science/blob/main/transcriptomics/notebooks/transcriptomics_analysis.ipynb)| [Multi-omics](https://colab.research.google.com/github/Multiomics-Analytics-Group/course_multi-omics_data_science/blob/main/multiomics/notebooks/multiomics_exercise.ipynb)|
|15:30-16:00| Coffee break| Coffee break| Coffee break| Coffee break|
|16:00-16:30| [Metagenomics Basic Analysis I](https://colab.research.google.com/github/Multiomics-Analytics-Group/course_multi-omics_data_science/blob/main/metagenomics/notebooks/metagenomics_analysis.ipynb)|[Network Exercises](https://colab.research.google.com/github/Multiomics-Analytics-Group/course_multi-omics_data_science/blob/main/notebooks/05_Visualising_Networks/04_nxpandas.ipynb)|[Graphical User Interface]()| Recap and Q&A
|16:30-17:00| [Metagenomics Basic Analysis II](https://colab.research.google.com/github/Multiomics-Analytics-Group/course_multi-omics_data_science/blob/main/metagenomics/notebooks/metagenomics_analysis.ipynb)| [Graphical User Interface]()|[Invited Speaker - Professor Carlos Muskus](https://scholar.google.com/citations?user=Yp6lnXQAAAAJ&hl=es)|Recap and Q&A|

## Further Resources

### References

1) [Empowering bioinformatics communities with Nextflow and nf-core](https://pubmed.ncbi.nlm.nih.gov/40731283/) *Björn E Langer, Andreia Amaral, Marie-Odile Baudement, Franziska Bonath, Mathieu Charles, Praveen Krishna Chitneedi, Emily L Clark, Paolo Di Tommaso, Sarah Djebali, Philip A Ewels, Sonia Eynard, James A Fellows Yates, Daniel Fischer, Evan W Floden, Sylvain Foissac, Gisela Gabernet, Maxime U Garcia, Gareth Gillard, Manu Kumar Gundappa, Cervin Guyomar, Christopher Hakkaart, Friederike Hanssen, Peter W Harrison, Matthias Hörtenhuber, Cyril Kurylo, Christa Kühn, Sandrine Lagarrigue, Delphine Lallias, Daniel J Macqueen, Edmund Miller, Júlia Mir-Pedrol, Gabriel Costa Monteiro Moreira, Sven Nahnsen, Harshil Patel, Alexander Peltzer, Frederique Pitel, Yuliaxis Ramayo-Caldas, Marcel da Câmara Ribeiro-Dantas, Dominique Rocha, Mazdak Salavati, Alexey Sokolov, Jose Espinosa-Carrasco, Cedric Notredame, The Nf-Core Community* [resource](<https://www.nextflow.io/>)

2) [nf-core/taxprofiler](https://www.biorxiv.org/content/10.1101/2023.10.20.563221v1) *Sofia Stamouli,  Moritz E. Beber, Tanja Normark,  Thomas A. Christensen II,  Lili Andersson-Li,  Maxime Borry, Mahwash Jamy, nf-core community,  James A. Fellows Yates* [resource](https://nf-co.re/taxprofiler/)

3) [nf-core/rnaseq](https://www.nature.com/articles/s41587-020-0439-x) *Philip A. Ewels, Alexander Peltzer, Sven Fillinger, Harshil Patel, Johannes Alneberg, Andreas Wilm, Maxime Ulysse Garcia, Paolo Di Tommaso, Sven Nahnsen* [resource](https://nf-co.re/rnaseq)

4) [quantms: a cloud-based pipeline for quantitative proteomics enables the reanalysis of public proteomics data](https://www.nature.com/articles/s41592-024-02343-1) *Chengxin Dai, Julianus Pfeuffer, Hong Wang, Ping Zheng, Lukas Käll, Timo Sachsenberg, Vadim Demichev, Mingze Bai, Oliver Kohlbacher, Yasset Perez-Riverol * [resource](https://nf-co.re/quantms)

5) [A technical review of multi-omics data integration methods: from classical statistical to deep generative approaches](https://academic.oup.com/bib/article/26/4/bbaf355/8220754) *Ana R Baião, Zhaoxiang Cai, Rebecca C Poulos, Phillip J Robinson, Roger R Reddel, Qing Zhong, Susana Vinga, Emanuel Gonçalves*

6) [Rhea, the reaction knowledgebase in 2022](https://pubmed.ncbi.nlm.nih.gov/34755880/) *Parit Bansal, Anne Morgat, Kristian B Axelsen, Venkatesh Muthukrishnan, Elisabeth Coudert, Lucila Aimo, Nevila Hyka-Nouspikel, Elisabeth Gasteiger, Arnaud Kerhornou, Teresa Batista Neto, Monica Pozzato, Marie-Claude Blatter, Alex Ignatchenko, Nicole Redaschi, Alan Bridge* [resource](https://www.rhea-db.org/)

7) [BacDive in 2022: the knowledge base for standardized bacterial and archaeal data](https://pubmed.ncbi.nlm.nih.gov/34718743/)*Lorenz Christian Reimer, Joaquim Sardà Carbasse, Julia Koblitz, Christian Ebeling, Adam Podstawka, Jörg Overmann* [resource](https://bacdive.dsmz.de/)

8) [TEMPURA: Database of Growth TEMPeratures of Usual and RAre Prokaryotes](https://pubmed.ncbi.nlm.nih.gov/32727974/)*Yu Sato, Kenji Okano, Hiroyuki Kimura, Kohsuke Honda* [resource](http://togodb.org/db/tempura)

9) [Exposome-Explorer 2.0: an update incorporating candidate dietary biomarkers and dietary associations with cancer risk](https://pubmed.ncbi.nlm.nih.gov/31724701/) *Vanessa Neveu, Geneviève Nicolas, Reza M Salek, David S Wishart, Augustin Scalbert* [resource](http://exposome-explorer.iarc.fr/)

10) [HMDB 5.0: the Human Metabolome Database for 2022](https://pubmed.ncbi.nlm.nih.gov/34986597/) *David S Wishart, AnChi Guo, Eponine Oler, Fei Wang, Afia Anjum, Harrison Peters, Raynard Dizon, Zinat Sayeeda, Siyang Tian, Brian L Lee, Mark Berjanskii, Robert Mah, Mai Yamamoto, Juan Jovel, Claudia Torres-Calzada, Mickel Hiebert-Giesbrecht, Vicki W Lui, Dorna Varshavi, Dorsa Varshavi, Dana Allen, David Arndt, Nitya Khetarpal, Aadhavya Sivakumaran, Karxena Harford, Selena Sanford, Kristen Yee, Xuan Cao, Zachary Budinski, Jaanus Liigand, Lun Zhang, Jiamin Zheng, Rupasri Mandal, Naama Karu, Maija Dambrova, Helgi B Schiöth, Russell Greiner, Vasuk Gautam* [resource](https://hmdb.ca/)

11) [MASI: microbiota—active substance interactions database](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7779062/) *Xian Zeng, Xue Yang, Jiajun Fan, Ying Tan, Lingyi Ju, Wanxiang Shen, Yali Wang, Xinghao Wang, Weiping Chen, Dianwen Ju, and Yu Zong Chen* [resource](http://www.aiddlab.com/MASI/)

12) [MicroPhenoDB Associates Metagenomic Data with Pathogenic Microbes, Microbial Core Genes, and Human Disease Phenotypes](https://pubmed.ncbi.nlm.nih.gov/33418085/) *Guocai Yao, Wenliang Zhang, Minglei Yang, Huan Yang, Jianbo Wang, Haiyue Zhang, Lai Wei, Zhi Xie, Weizhong Li* [resource](http://www.liwzlab.cn/microphenodb)

13) [iModulonDB: a knowledgebase of microbial transcriptional regulation derived from machine learning](https://pubmed.ncbi.nlm.nih.gov/33045728/) *Kevin Rychel, Katherine Decker, Anand V Sastry, Patrick V Phaneuf, Saugat Poudel, Bernhard O Palsson* [resource](https://imodulondb.org/index.html)

14) [The Natural Products Atlas 2.0: a database of microbially-derived natural products](https://pubmed.ncbi.nlm.nih.gov/34718710/) *Jeffrey A van Santen, Ella F Poynton, Dasha Iskakova, Emily McMann, Tyler A Alsup, Trevor N Clark, Claire H Fergusson, David P Fewer, Alison H Hughes, Caitlin A McCadden, Jonathan Parra, Sylvia Soldatou, Jeffrey D Rudolf, Elisabeth M-L Janssen, Katherine R Duncan, Roger G Linington* [resource](https://www.npatlas.org/)

15) [MIBiG 3.0: a community-driven effort to annotate experimentally validated biosynthetic gene clusters](https://pubmed.ncbi.nlm.nih.gov/36399496/) *Barbara R Terlouw, Kai Blin, Jorge C Navarro-Muñoz, ..., Dong Yang, Jingwei Yu, Mitja Zdouc, Zheng Zhong, Jérôme Collemare, Roger G Linington, Tilmann Weber, Marnix H Medema* [resource](https://mibig.secondarymetabolites.org/)

16) [The National Microbiome Data Collaborative: enabling microbiome science](https://pubmed.ncbi.nlm.nih.gov/32350400/) *Elisha M Wood-Charlson, Anubhav, Deanna Auberry, Hannah Blanco, Mark I Borkum, Yuri E Corilo, Karen W Davenport, Shweta Deshpande, Ranjeet Devarakonda, Meghan Drake, William D Duncan, Mark C Flynn, David Hays, Bin Hu, Marcel Huntemann, Po-E Li, Mary Lipton, Chien-Chi Lo, David Millard, Kayd Miller, Paul D Piehowski, Samuel Purvine, T B K Reddy, Migun Shakya, Jagadish Chandrabose Sundaramurthi, Pajau Vangay, Yaxing Wei, Bruce E Wilson, Shane Canon, Patrick S G Chain, Kjiersten Fagnan, Stanton Martin, Lee Ann McCue, Christopher J Mungall, Nigel J Mouncey, Mary E Maxon, Emiley A Eloe-Fadrosh* [resource](https://data.microbiomedata.org/)

### Cheat Sheets

- Basics:
  - [Getting started](cheat_sheets/cheat_sheet_day0.pdf)
  - [Importing Data](cheat_sheets/Importing_Data_Cheat_sheet.pdf)
  - [Jupyter Notebook](cheat_sheets/Jupyter_Notebook_Cheat_Sheet.pdf)
- Data Science:
  - [Numpy](cheat_sheets/Numpy_Python_Cheat_Sheet.pdf)
  - [Pandas](cheat_sheets/Pandas_Cheat_Sheet.pdf)
  - [Scipy](cheat_sheets/Scipy-LinearAlgebra_Cheat_Sheet.pdf)
  - [Scikit-learn](cheat_sheets/Scikit-learn_Cheat_Sheet.pdf)
- Visualization:
  - [Matplotlib](cheat_sheets/Python_Matplotlib_Cheat_Sheet.pdf)
  - [Plot.ly](cheat_sheets/Plotly_Cheat_Sheet.pdf)
  - [Seaborn](cheat_sheets/Seaborn_Cheat_Sheet.pdf)
  - [Bokeh](cheat_sheets/Bokeh_Cheat_Sheet.pdf)

### Basics

- [learnpython.org](https://www.learnpython.org/)
  - interactive python basics tutorial

- [Springboard - Data Analysis with Python, SQL, and R](https://www.springboard.com/learning-paths/data-analysis/learn/)
  - starts with - [Solo Learn](https://www.sololearn.com/Course/Python/) and [Design of Computer Programs](https://www.udacity.com/course/design-of-computer-programs--cs212)
- [Scipy Lectures](https://scipy-lectures.org/index.html)
  - Python introduction with a focus on scientific computing
- [official tutorial](https://docs.python.org/3/tutorial/)

### Python Installations

In this course we use [Google Colab](https://colab.research.google.com/) to execute notebooks. Notebooks are text files allowing the combination of Text, Code and the output of code. Colab offers an extended set of pre-installed tools. See the [tutorial series](https://www.youtube.com/playlist?list=PLQY2H8rRoyvyK5aEDAI3wUUqC_F0oEroL).

[Anaconda](https://www.anaconda.com/products/individual) offers for your private computer an extended installations, including most tools you will ever need for Python.

## Acknowledgements

Some of the slides and notebooks have been inspired or reused from the Data [Science Platform](https://multiomics-analytics-group.github.io/data-science-platform/) at the [Informatics Platform](https://www.biosustain.dtu.dk/technologies/biofoundry/informatics) the Novo Nordisk Foundation Center for Biosustainability at the [Technical University of Denmark](https://www.dtu.dk/). 

Some notebooks have been inspired by the course [Python Tsunami](https://github.com/Center-for-Health-Data-Science/PythonTsunami) at the [Center for Health Data Science (HeaDS)](https://heads.ku.dk/) at the [University of Copenhagen](https://www.ku.dk/).
