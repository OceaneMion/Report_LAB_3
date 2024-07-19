## Biological context
<div align="center">
  <img src="https://github.com/OceaneMion/Report_LAB_3/blob/main/Images/bat.png" alt="bat" width="800"/>
  <p style="color: darkgray; font-style: italic;">
    Photography of a bat infected by Pseudogymnoascus destructans (National Park Service)
  </p>
</div>






White-nose disease, caused by the fungus *Pseudogymnoascus destructans*, has significantly impacted bat populations in Eurasia and North America. Understanding the evolutionary and pathogenic mechanisms of this fungus is crucial for developing effective strategies against the disease. For this purpose, my internship focused on studying the interplay between transposable elements (TEs) as drivers of genome evolution often found near genes encoding virulence factors, and DNA methylation. DNA methylation, particularly 5-methylcytosine (5mC), is a key epigenetic mechanism that impacts TE dynamics by their silencing, which prevents their transposition and therefore impact on pathogenicity. Using Nanopore sequencing data, I conducted a comparative genomic analysis of 11 pathogenic P. destructans isolates from two lineages (Pd-1, Pd-2) with specialized host preference and a supposed non-pathogenic outgroup (*Pseudogymnoascus spp*).

## Bioinformatic pipeline

My internship focused on the creation of a bioinformatic pipeline to study the association between methylation and transposable elements (TEs) in P.destructans. Analysis were performed in the following order:

* Nanopore Sequencing of 11 P.destructans isolates + outgroup (already performed See [Nanopore_Sequencing](https://github.com/OceaneMion/Report_LAB_3/blob/main/Jupyter%20_Notebook/1%29%20Nanopore_Sequencing.ipynb))

* Basecalling (Dorado, Guppy) (See [Basecalling](https://github.com/OceaneMion/Report_LAB_3/blob/main/Jupyter%20_Notebook/2%29%20Basecalling.ipynb))
* Control quality (QC) of basecalling (See [QC_analysis](https://github.com/OceaneMion/Report_LAB_3/blob/main/Jupyter%20_Notebook/3%29%20QC_analysis.ipynb))
* Adapters trimming from basecall reads (See [Trimming](https://github.com/OceaneMion/Report_LAB_3/blob/main/Jupyter%20_Notebook/4%29%20Trimming_adapters.ipynb))
* Assemblies contructs from basecalls reads (See [Assemblies](https://github.com/OceaneMion/Report_LAB_3/blob/main/Jupyter%20_Notebook/5%29%20Assemblies.ipynb))
* Polishing of Assemblies (See [Polishing](https://github.com/OceaneMion/Report_LAB_3/blob/main/Jupyter%20_Notebook/6%29%20Polishing_Assemblies.ipynb))
* Control quality (QC) of assemblies (See [Quality Assemblies](https://github.com/OceaneMion/Report_LAB_3/blob/main/Jupyter%20_Notebook/7%29%20Quality_Assembly.ipynb))
* Contaminants removal (See [Contaminant](https://github.com/OceaneMion/Report_LAB_3/blob/main/Jupyter%20_Notebook/8%29%20Removing_contaminants.ipynb))
* Methylation analysis (See [Methylation](https://github.com/OceaneMion/Report_LAB_3/blob/main/Jupyter%20_Notebook/9%29%20Methylation_analysis.ipynb))
* TEs analysis (See [TEs](https://github.com/OceaneMion/Report_LAB_3/blob/main/Jupyter%20_Notebook/10%29%20TEs_analysis.ipynb))
* Association between methylation and TEs (TO BE UPLOAD SOON)

<div align="center">
  <img src="https://github.com/OceaneMion/Report_LAB_3/blob/main/Images/workflow.png" alt="bat" width="800"/>
  <p style="color: darkgray; font-style: italic;">
    Workflow of analysis for TEs and methylation
  </p>
</div>
