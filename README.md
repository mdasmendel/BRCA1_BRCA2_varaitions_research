# BRCA1 BRCA2 Variations Research

## Description

This project aims to extract and analyze genetic variations from full genomes with a specific focus on BRCA1 and BRCA2 genes. The analysis is carried out using two Jupyter Notebooks: `extract-variations-for-genes.ipynb` and `get-cancer-genes-clinvar.ipynb`, located in the "notebooks" folder.

The main objective of this project is to index reference genomes and patient genomes, generate a VCF (Variant Call Format) file with the identified genetic variations specific to BRCA1 and BRCA2 genes, and compare these variations with known mutations in the ClinVar database related to cancer.

## Notebooks

1. `extract-variations-for-genes.ipynb`: This notebook is responsible for extracting the genetic variations from full genomes for specific genes of interest.

2. `get-cancer-genes-clinvar.ipynb`: This notebook compares the extracted variations with the ClinVar database to identify any variations known to be associated with cancer. For now, it simply prints the matched variations.

## Getting Started

### Prerequisites

To run the notebooks and execute the code successfully, you need the following prerequisites:

- Linux family system
- Python (version 3.x)
- Jupyter Notebook
- [GATK (Genome Analysis Toolkit)](https://gatk.broadinstitute.org/) (version 4.x)
- [Conda](https://conda.io/) (version X.X.X)

## Setup Instructions

### Installing Conda

1. Visit the [Conda website](https://conda.io/) and follow the installation instructions for your operating system.
2. After Conda is installed, open a terminal and run the following commands to create and activate a new Conda environment:

   ```bash
   conda create -n myenv python=X.X
   conda activate myenv
   ```

   Replace `myenv` with the desired name for your environment and `X.X` with the desired Python version.

### Installing Samtools with Conda

To install Samtools using Conda, run the following command:

```bash
conda install -c bioconda samtools
```

### Installing GATK with Conda

To install GATK using Conda, run the following command:

```bash
conda install -c bioconda gatk
```

For detailed information on how to use GATK and its various tools, refer to the official [GATK documentation](https://gatk.broadinstitute.org/documentation/).

### Installation

1. Clone this repository:

```bash
git clone https://github.com/mdasmendel/BRCA1_BRCA2_varaitions_research.git
```

2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Usage

1. Open Jupyter Notebook:

```bash
jupyter notebook
```

2. Navigate to the "notebooks" folder.

3. Open the `extract-variations-for-genes.ipynb` notebook and follow the instructions to provide the paths to the reference genomes and patient genomes. Execute the cells to extract genetic variations for the genes of interest and generate a VCF file.

4. Open the `get-cancer-genes-clinvar.ipynb` notebook. This notebook will take the VCF file generated by the first notebook and compare the variations with known mutations in the ClinVar database.

5. The resulting matches will be printed out.

## Contributing

If you want to contribute to this project, you can follow these steps:

1. Fork this repository.
2. Create a new branch: `git checkout -b feature/your-feature`.
3. Make your changes and commit them: `git commit -m

 'Add some feature'`.
4. Push to the branch: `git push origin feature/your-feature`.
5. Submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

If you have any questions or suggestions regarding this project, please feel free to contact [Mihai Dascal] via [dascal.mi@gmail.com].