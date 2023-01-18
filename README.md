# FINRISK - HEART FAILURE AND MICROBIOME

Repository of Bioinformatics Intelligent Systems's project integrated in the Master's Degree in Bioinformatics at University of Minho, 2022/2023.

**Members**:
<ul>
  <li>Adriano Silva PG43176</li>
  <li>Rui Gomes PG45970</li>
  <li>Sérgio Mendes PG42486</li>
</ul>

The goal of this challenge is to predict incident heart failure based on clinical and microbiome data, taking into account the time of the event.

-----------
**DATASET**

The FINRISK cohort data is divided in random subsets for training, test and scoring subsets. The FINRISK cohort includes 7,231 adult stool samples (54% participation rate) collected in 2002 and including 15 years follow up (currently available until the end of 2019). Challenge Data includes synthetic data based on FINRISK population cohort study.
The synthetic data is provided in csv format:

train
<ul>
 <li>pheno_train.csv</li>
  <li>readcounts_train.csv</li>
  <li>taxtable.csv</li>
</ul>

test
<ul>
 <li>pheno_test.csv</li>
  <li>readcounts_test.csv</li>
  <li>taxtable.csv</li>
</ul>

<ol>
 <li>Host phenotype data (pheno_*.csv): Individuals in rows and metadata variables in columns.</li>
  <li>Taxonomic abundance table (readcounts_*.csv): Individuals in columns and taxon names (complete taxonomic hierarchy from Kingdom, Phylum, Class, Order, Family, Genus to Species) in rows. The taxonomic abundance table contains the sequence read counts.</li>
  <li>Taxonomic mapping table (taxtable.csv): Mapping of the taxonomic species to higher taxonomic hierarchy (Kingdom, Phylum, Class, Order, Family, Genus and Species)</li>
</ol>














