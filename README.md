# Bioinformatics-Assignment-Toolkit

The project includes various bioinformatics tasks such as DNA sequence processing, protein classification, and clustering based on amino acid usage. Each task is broken down into functions designed to solve specific problems related to genomics and proteomics.

# Features
- Primers and Melting Temperature: Reads DNA sequences from FASTA files. Computes the complement of sequences. Generates primers and computes their melting temperatures.

- Translation and Reading Frames: Translates DNA sequences into amino acid sequences across all reading frames. Locates the longest Open Reading Frame (ORF). Outputs the translated ORF in FASTA format.

- Amino Acid Classification: Analyzes amino acid sequences. Computes statistics on amino acid properties: polar, small, and hydrophobic residues.

- Protein Clustering: Calculates Euclidean distances between proteins based on amino acid composition. Generates a distance matrix to cluster proteins.

How to Use
Clone this repository:

bash
Copy code
git clone https://github.com/yourusername/Bioinformatics-Assignment-Toolkit.git
cd Bioinformatics-Assignment-Toolkit
Install necessary libraries:

bash
Copy code
pip install -r requirements.txt
Run the provided scripts in a Jupyter notebook or Python environment.

Project Structure
primers.py: Handles primer extraction and melting temperature calculations.
translation.py: Translates DNA sequences into proteins.
classification.py: Analyzes amino acid composition.
clustering.py: Clusters proteins based on amino acid properties.
Tests
To verify that your functions work as expected, run the provided test cases within each module. You can test individual components as shown in the included code.

License

This project is licensed under the MIT License.

Contact

For queries, please contact Monty Nkpa. Connect with me on LinkedIn: https://www.linkedin.com/in/monty-nkpa-7a4a7623b/?originalSubdomain=uk
