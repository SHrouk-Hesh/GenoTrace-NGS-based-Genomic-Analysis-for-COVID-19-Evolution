# GenoTrace-NGS-based-Genomic-Analysis-for-COVID-19-Evolution
Introducing GenoTrace, an innovative project utilizing Next-Generation Sequencing (NGS)-based methods to explore the evolution and spread of the coronavirus disease (COVID-19). As a newly discovered coronavirus causing an infectious disease, understanding its origins, and genetic variations is crucial in combating the pandemic effectively. 

![image](https://github.com/SHrouk-Hesh/GenoTrace-NGS-based-Genomic-Analysis-for-COVID-19-Evolution/assets/121517766/5f42f032-2c63-4f8f-b3f5-ebe379136ad8)


**Key Objectives:**

1. **Sequencing and Data Collection:** GenoTrace downloads COVID-19 data from the NCBI database, acquiring crucial genetic information from various time points to track the evolution of the infectious agent.

2. **Multiple Sequence Alignment:** We perform multiple sequence alignment for the collected COVID-19 samples, enabling us to identify genetic variations and trace evolutionary patterns in the viral genome.

3. **Phylogenetic Tree Generation:** Utilizing the aligned sequences, GenoTrace generates a phylogenetic tree to visualize the genetic relationships between different viral strains. This tree provides insights into the virus's diversification and spread.

4. **Comparative Analysis with Other Viruses:** By employing BLAST, we align the COVID-19 spike protein with spike proteins from other viral strains. This analysis identifies homologous proteins and aids in understanding potential similarities and differences in pathogenicity.

5. **Annotation and Insights:** GenoTrace selects the most homologous protein and annotates it using NCBI and Uniprot databases. These annotations provide valuable information about the protein's function and evolutionary significance.

![image](https://github.com/SHrouk-Hesh/GenoTrace-NGS-based-Genomic-Analysis-for-COVID-19-Evolution/assets/121517766/672eefa0-6dfc-46f6-9b34-aa28c8618c91)
![image](https://github.com/SHrouk-Hesh/GenoTrace-NGS-based-Genomic-Analysis-for-COVID-19-Evolution/assets/121517766/ca2d9463-d56e-4e4c-a875-6ef3428a6664)

After we extracted the data from "NCBI Covid-19“ which are "20 samples" with different Lineage with "fasta format", then performing multiple sequence alignment for our 20 samples using "Muscle Alignment".


![image](https://github.com/SHrouk-Hesh/GenoTrace-NGS-based-Genomic-Analysis-for-COVID-19-Evolution/assets/121517766/2685e9d8-23c0-4f49-8feb-3259d0fb1985)
![image](https://github.com/SHrouk-Hesh/GenoTrace-NGS-based-Genomic-Analysis-for-COVID-19-Evolution/assets/121517766/c29d8026-f655-4bb1-9855-ca0e455a3385)

Phylogenetic Tree Visualized



![image](https://github.com/SHrouk-Hesh/GenoTrace-NGS-based-Genomic-Analysis-for-COVID-19-Evolution/assets/121517766/643f2417-86f6-48cb-a68e-db8cc49df09d)
![image](https://github.com/SHrouk-Hesh/GenoTrace-NGS-based-Genomic-Analysis-for-COVID-19-Evolution/assets/121517766/f60143d5-b6cd-4486-b0d9-42d47b9c1616)

After we have chosen the most homologous gene based on the criteria upon E-value, bit score, coverage. Next, we searched for the gene in other databases and mentioned its cellular and molecular function and how it affects the disease.
So, we have chosen our best sequences which is: 
•	KT182953.1 Middle East respiratory syndrome coronavirus  
After that, we used NCBI to get “Protein ID” and Uniport to mention in detail the function of the protein, gene ontology, cellular and molecular function and how it affects the disease.


**Impact and Significance:**

By investigating the genomic sequence of SARS-CoV-2 at different time points, GenoTrace contributes to our understanding of COVID-19 evolution. This knowledge is vital for developing effective molecular diagnostic tests, treatments, and vaccines. Additionally, the project provides essential data to support the formulation of successful measures and strategies to mitigate the spread of the pandemic during different phases.

GenoTrace plays a crucial role in advancing our comprehension of infectious diseases, enabling researchers and healthcare professionals to make informed decisions and implement targeted interventions. Our project stands at the forefront of the fight against COVID-19, driven by the pursuit of knowledge and the commitment to safeguard global health.

In the face of this global crisis, GenoTrace serves as a beacon of hope, harnessing the potential of NGS-based genomic analysis to illuminate the path toward a brighter, healthier future for humanity.
