
Structuring a data science project

It is important to have a clear structure of the project, such that several people can work 
together

- README.md   (description of project)

- .gitignore  (we do not want to put data/pdbs and data/fasta under git control)

- notes  (documentation and notes, just use reasonable filenames)

- data
    - ab_ag.tsv, ...
    - pdbs     (downloaded pdbs data)
    - fasta    (created fasta files)

- notebooks
    - preprocess     (QC, data cleaning)
    - contact_points
    - SASA
    - analysis1
    - analysis2

- generated           (data that will be kept)
    - preprocess      (outputs from notebooks/preprocess)
    - contact_points  (compute contact points)
    - SASA            (compute SASA)
    - analysis1       (first analysis)
    - analysis2       (second analysis)


The idea of having the generated folder is that we can modularize the analysis and development.



