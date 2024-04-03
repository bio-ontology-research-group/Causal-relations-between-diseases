# Causal relations between diseases
 This repository is for our paper: **Causal relationships between diseases mined from the literature improve the use of polygenic risk scores**

 
The paper discusses the creation of a Directed Acyclic Graph (DAG) for causal relations between diseases mapped to ICD10 identifiers and its use to improve polygenic risk scores.
An interactive visualization of the DAG can be found [here](https://cosmograph.app/run/?data=https://raw.githubusercontent.com/stoonsi/Causal-relations-between-diseases/main/data/DDC_DAG.tsv&meta=https://raw.githubusercontent.com/stoonsi/Causal-relations-between-diseases/main/data/meta.tsv&gravity=0.48&repulsion=1.99&repulsionTheta=1.92&linkSpring=0.16&linkDistance=19&friction=0.93&renderLabels=true&renderHoveredLabel=true&renderLinks=true&linkArrows=true&nodeSizeScale=1.2&linkWidthScale=0.1&linkArrowsSizeScale=0.5&nodeSize=size-default&nodeColor=color-category&nodeLabel=id&linkWidth=width-avg-score&linkColor=color-avg-score&).

![image](https://github.com/stoonsi/Causal-relations-between-diseases/assets/63608176/b2a2ca43-c4c1-4ad5-b21c-79bb86c0dae8)

The used data is available as follows:

- The main DAG with various metrics included can be found in:
  - data/DDC_DAG.tsv
- The used dictionary of ICD10 names can be found in:
  - data/disease_dict.json
- The expert curated data that was used for evalution can be found in:
  - data/curated_positive_relations.tsv for curated positive relations
  - data/curated_negative_relations.tsv for curated negative relations
