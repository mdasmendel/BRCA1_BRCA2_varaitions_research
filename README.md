# BRCA1 BRCA2 variations research

## Description

This project aims to extract genetic variations from full genomes using the "extract-variations-from-full-genome.ipynb" Jupyter Notebook. The notebook is located in the "notebooks" folder.

The main objective of this project is to index reference genomes and patient genomes and generate a VCF (Variant Call Format) file as output. The VCF file will contain information about the identified genetic variations, such as single nucleotide polymorphisms (SNPs), insertions, deletions, and other genetic variants.

## Getting Started

### Prerequisites

To run the notebook and execute the code successfully, you need the following prerequisites:

- Linux family system
- Python (version 3.x)
- Jupyter Notebook
- [GATK (Genome Analysis Toolkit)](https://gatk.broadinstitute.org/) (version 4.x)
- [Conda](https://conda.io/) (version X.X.X)

### Installing Conda

1. Visit the [Conda website](https://conda.io/) and follow the installation instructions for your operating system.

2. Once Conda is installed, open a terminal and run the following command to create a new Conda environment:

   ```bash
   conda create -n myenv python=X.X
   ```

   Replace `myenv` with the desired name for your environment and `X.X` with the desired Python version.

3. Activate the Conda environment:

   ```bash
   conda activate myenv
   ```

### Installing Samtools with Conda

To install Samtools using Conda, run the following command:

```bash
conda install -c bioconda samtools
```

This command will install Samtools from the Bioconda channel, which provides bioinformatics-related packages.

### Installing GATK with Conda

To install GATK using Conda, run the following command:

```bash
conda install -c bioconda gatk
```

This command will install GATK from the Bioconda channel.

For detailed information on how to use GATK and its various tools, refer to the official [GATK documentation](https://gatk.broadinstitute.org/documentation/).

Make sure to replace `X.X.X` with the specific versions of GATK and Conda you require for your project. You can also add any other relevant instructions or dependencies as needed.

Remember to provide clear instructions and any additional setup steps necessary for users to install and configure these dependencies in their environment.

## Installation

1. Clone this repository:

```bash
git clone https://github.com/your-username/project.git
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

2. Navigate to the "notebooks" folder and open the "extract-variations-from-full-genome.ipynb" notebook.

3. Follow the instructions in the notebook to provide the paths to the reference genomes and patient genomes.

4. Execute the cells in the notebook to process the data and generate the VCF file.

5. The resulting VCF file will be saved in the specified output directory.

## Contributing

If you want to contribute to this project, you can follow these steps:

1. Fork this repository.
2. Create a new branch: `git checkout -b feature/your-feature`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature/your-feature`.
5. Submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

If you have any questions or suggestions regarding this project, please feel free to contact [Mihai Dascal] via [dascal.mi@gmail.com].