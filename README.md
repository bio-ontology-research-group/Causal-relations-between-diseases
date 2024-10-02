# Causal relations between diseases
 This repository is for our paper: **Causal relationships between diseases mined from the literature improve the use of polygenic risk scores**

 
The paper discusses the creation of a Directed Acyclic Graph (DAG) for causal relations between diseases mapped to ICD-10-CM identifiers and its use to improve polygenic risk scores.
An interactive visualization of the DAG can be found [here](https://cosmograph.app/run/?data=https://raw.githubusercontent.com/stoonsi/Causal-relations-between-diseases/main/data/DDC_DAG.tsv&meta=https://raw.githubusercontent.com/stoonsi/Causal-relations-between-diseases/main/data/meta.tsv&gravity=0.48&repulsion=1.99&repulsionTheta=1.92&linkSpring=0.16&linkDistance=19&friction=0.93&renderLabels=true&renderHoveredLabel=true&renderLinks=true&linkArrows=true&nodeSizeScale=1.2&linkWidthScale=0.1&linkArrowsSizeScale=0.5&nodeSize=size-default&nodeColor=color-category&nodeLabel=id&linkWidth=width-avg-score&linkColor=color-avg-score&).

![image](https://github.com/stoonsi/Causal-relations-between-diseases/assets/63608176/187c24e9-2d88-43ce-8b8d-9fac1c473279)

The used data is available as follows:
- The Disease Ontology version we used is available through [this link](https://raw.githubusercontent.com/DiseaseOntology/HumanDiseaseOntology/v2023-01-30/src/ontology/doid.owl)
- The main DAG with various metrics included can be found in:
  - data/DDC_DAG.tsv
- The full cyclic graph
  - data/DDC_full_graph.tsv
- The used dictionary of ICD10 names can be found in:
  - data/disease_dict.json
- The expert curated data that was used for evalution can be found in:
  - data/curated_positive_relations.tsv for curated positive relations
  - data/curated_negative_relations.tsv for curated negative relations
- The autmatically generated Polygenic Risk Scores (PRSs) can be downloaded via [this link](https://bio2vec.cbrc.kaust.edu.sa/data/BORD/PRS_files.zip)
