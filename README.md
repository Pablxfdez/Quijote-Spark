# Quijote-Spark Repository

This repository is dedicated to the processing and transformation of the text file `quijote.txt`, which contains the famous literary work "Don Quixote". The transformations are performed using two Python scripts, `random_lines.py` and `word_count.py`, and are executed in a Spark cluster environment.

## Repository Contents:

1. **quijote.txt**
   - **Description**: The original text file of "Don Quixote". This file serves as the base for all subsequent transformations and analyses.

2. **random_lines.py**
   - **Description**: This script selects random lines from `quijote.txt` based on a ratio provided via the command line. The output of this script is `quijote_s05.txt`, which contains a subset of the original text.

3. **quijote_s05.txt**
   - **Description**: The result of applying `random_lines.py` to `quijote.txt`. This file contains a randomly selected subset of lines from the original text.

4. **word_count.py**
   - **Description**: This script performs a word count analysis on the text files. It takes `quijote_s05.txt` and the original `quijote.txt` as input parameters and produces `out_quijote_s05.txt` and `out_quijote.txt`, respectively.

5. **out_quijote_s05.txt** and **out_quijote.txt**
   - **Description**: These files contain the output of the word count analysis performed by `word_count.py`. They provide insights into the frequency of words in both the original text and the randomly selected subset.

6. **Spark Cluster Interface Images**
   - **Description**: Images of the Spark cluster interface, demonstrating the execution of the scripts. These images serve as proof of the processing being carried out in a Spark environment, with the user `Pabfer1`.

## Workflow and Execution:

- The process begins with the `random_lines.py` script, which randomly selects lines from `quijote.txt` to create a new file, `quijote_s05.txt`.
- The `word_count.py` script is then used to analyze both `quijote.txt` and `quijote_s05.txt`, producing word count outputs in `out_quijote.txt` and `out_quijote_s05.txt`, respectively.
- All operations are performed in a Spark cluster, and the process is initiated through the Linux terminal.
- The repository includes images from the Spark cluster interface, showcasing the execution of the scripts and the involvement of the user `Pabfer1`.
