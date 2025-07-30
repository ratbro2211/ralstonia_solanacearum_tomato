🧬 Ralstonia solanacearum Tomato Genome Project
This repository documents a comprehensive bioinformatics pipeline for analyzing Ralstonia solanacearum, a bacterial plant pathogen affecting tomato plants. The analysis includes read preprocessing, genome assembly, annotation, quality assessment, and effector prediction.

📁 Project Directory Structure
<pre> Ralstonia_solanacearum_tomato/ │ ├── raw_data/ # Raw FASTQ sequencing files ├── Results/ │ ├── trimmomatic/ # Adapter-trimmed, quality-filtered reads │ ├── spades_assembly/ # SPAdes assembly output │ ├── ragtag_scaffolded_assembly/ # Reference-guided scaffolding │ ├── prokka_annotation/ # Genome annotation by Prokka │ ├── busco/ # BUSCO genome completeness assessment │ ├── quast/ # QUAST assembly metrics │ └── interproscan/ # Functional annotation of proteins │ ├── Code/ # All Jupyter notebooks and scripts │ └── Ralstonia_solanacearum_tomato.ipynb └── README.md # Project overview </pre>

| Tool             | Purpose                                     |
| ---------------- | ------------------------------------------- |
| **Trimmomatic**  | Read quality control and adapter removal    |
| **SPAdes**       | De novo genome assembly                     |
| **RagTag**       | Reference-guided scaffolding                |
| **Prokka**       | Structural & functional genome annotation   |
| **QUAST**        | Assembly statistics & contiguity metrics    |
| **BUSCO**        | Genome completeness analysis                |
| **InterProScan** | Functional domain prediction                |
| **FastANI**      | Average Nucleotide Identity with references |


🧪 Workflow Summary
Raw Read Preprocessing using Trimmomatic

De novo Assembly with SPAdes

Assembly Scaffolding using RagTag and a reference genome

Annotation with Prokka

Assembly Quality Checks with QUAST and BUSCO

Effector Prediction Pipeline using InterProScan, SignalP, and more


📓 Jupyter Notebook
The primary notebook Ralstonia_solanacearum_tomato.ipynb contains:

All commands executed step by step

Explanations for each tool and parameter

Output interpretation

Quality control plots and summaries

🔬 Biological Relevance
Ralstonia solanacearum is a devastating bacterial pathogen. Understanding its genomic structure, gene functions, and effector proteins is vital for:

Improved diagnostics

Developing resistant cultivars

Studying plant-pathogen interactions

