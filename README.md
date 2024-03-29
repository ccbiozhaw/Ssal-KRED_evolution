# Paper data

### Data and code to reproduce our results

library 9 and library 10 contain the training data and results for their respective library

library9/10_training.ipynb - jupyter notebook with our code. the cells can be executed in order from top to bottom. The notebook was already pre-run, and the expected outputs are visible. The only requirements are for the data files to be in the same directory as the jupyter notebook file. The runtime for library9 should not exceed a couple of minutes, even on a standard laptop. This increases manyfold for library10, as making the predictions for all 20\*\*5 variants is very expensive. You can reduce this by setting testing to True. To make predictions on your own data, your inputs have to adhere strictly to the format of our own data, or the code has to be adjusted respectively.

library9/10_data.xlsx - the target value is defined as slope variant / slope wild-type. the slope is derived from the UV-assay.

aaindex.csv - AAindex is a database of numerical indices representing various physicochemical and biochemical properties of amino acids and pairs of amino acids. This is used to represent amino acids. [1,2]

[1] Kawashima, S. and Kanehisa, M.; AAindex: amino acid index database. Nucleic Acids Res. 28, 374 (2000). [PMID:10592278]

[2] Kawashima, S., Pokarowski, P., Pokarowska, M., Kolinski, A., Katayama, T., and Kanehisa, M.; AAindex: amino acid index database, progress report 2008. Nucleic Acids Res. 36, D202-D205 (2008).[PMID:17998252]

# System Requirements

## Hardware requirements

To run this code and reproduce our results, only a standard computer is required.

Software requirements
We installed the anaconda python distribution from: https://www.anaconda.com/products/individual and followed their download instructions. The specific versions we used for our analysis can be found in requirements.txt

# Installation requirements

this repository can be downloaded to your local machine via the command:

git clone https://github.com/ccbiozhaw/Ssal-KRED_evolution

this should only take a few seconds.

# References
This code originates from the following publication:

https://www.nature.com/articles/s42004-024-01130-5

If you utilize this code, please cite:

https://www.nature.com/articles/s42004-024-01130-5

https://www.nature.com/articles/s41467-022-27999-1
