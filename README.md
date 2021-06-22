# PROMISE
Model and code files for FDA opioid systems model (UPDATE WITH MORE DETAIL ONCE PAPERS SUBMITTED).

For any questions please contact [Tse Yang Lim](mailto:tylim@mit.edu)

### Analysis & Graphing
Contains the Vensim model files and Python code (in .ipynb and .py formats) used for model estimation, analysis, and graphing of results. This is the 'working' directory of this repo.

### Data
Contains Excel data and documentation files, as well as data pre-processing code (CELIA UPDATE THIS DESCRIPTION LATER).

### Replication Package
Minimal file and code package needed to replicate the analysis 'from scratch', without any pre-generated results or figures. **Use this to directly replicate the complete model estimation & analysis process.** To do so:
1. Make a local copy of this folder
2. Update the ControlFile OICC\*.txt according to the instructions in (README FILE NAME HERE)
3. First, run OIC-OO v6.ipynb / .py
4. Then run OSM Results Processing.ipynb / .py
5. Then run the desired Graphing .ipynb / .py code in any order 

**Important:** The model estimation code is intended to work with an experimental parallelised Vensim engine. With appropriate modifications to the main function calls (but not the analytical procedure), the same analysis can be run on regular commercially available Vensim DSS, though it will take *much* longer. Please contact [Tom Fiddaman](mailto:tom@ventanasystems.com) for information on the experimental Vensim engine.

### Results Summary
Contains main estimation results and output tables and figures used in the paper, including summary output files from various robustness and sensitivity analyses. **Figures and results can be downloaded directly here.**

### Vensim Files
Contains the main Vensim model file (.mdl) and other supplementary Vensim files used for model estimation (e.g. optimization control, payoff definition, savelist files, and so on).