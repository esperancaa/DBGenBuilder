This repository contains a project where a database from scratch is created, with the objective of using the genebank database but with an optimization.
 
The 'Final' folder contains the final project which is divided into 3 folders:

The "Database" folder which contains:
- The conceptual model: "Data_Base_IAP.pdf" / "Conceptual_model.eddx"
- The logical model: "Logic_model.pdf" / "Logic_model.mwb"
- The document with all the necessary entities, attributes and cardinalities: "Entities, attributes and cardinalities.pdf"
The "Script" folder which contains:
- The script with all the code used to extract information and populate it in the Database : "Script_final.ipynb"
The "Report and Presentation" folder which contains:
- Report document with the documentation of the project: "Relatório_final.pdf"
- The PowerPoint presentation of the project: "Apresentação_final.ppt"


Notes:
- DB has a particularity of where id of CDS, or Uniprot, or Authors, or Afilliation or Pubmed has always 1 result, 
never being empty. This happens because when there is no actual id/or name associated to those entities, the result is 
"N/A", or "N/A_CDS" or "N/A_Uniprot".