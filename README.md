# LazBFDEF
Code for [*Substrate Prediction for RiPP Biosynthetic Enzymes via Masked Language Modeling and Transfer Learning*](https://arxiv.org/abs/2402.15181).

<!--Trained model weights can be accessed [here](https://drive.google.com/drive/folders/104klsza_oNzCbj3UOgczbsuUQ1VAy9K0?usp=drive_link).-->

All data needed to reproduce the results can be found [here](https://drive.google.com/drive/folders/1hDGo4JQDic0i8sRVqtTpIuD0PtE0TsXH?usp=drive_link). Descriptions of the data files can be found in `DATA.md`

Trained model weights can be accessed [here](https://huggingface.co/jjoecclark).

## Reproducing the work

All results can be reproduced by running the `.ipynb` notebooks contained in the `scripts` folder. The code can either be run on Google Colab or locally. If using Google Colab, one can simply upload and the files and run the optional `pip install` cells to install the required packages as needed. If running the code locally, one can create a conda enviornment using the `env.yml` which describes the versions of all software libraries used in this work.

The Jupyter notebooks are numbered based on the order in which they should be run (i.e., start with `1_VanillaESMEmbeddings.ipynb`). Each notebook contains comments which guides the user through the code. Below is a brief description of each notebook and its purpose.

- `1_VanillaESMEmbeddings.ipynb`

2_LazBFESMEmbeddings.ipynb

3_LazDEFESMEmbeddings.ipynb

4_PeptideESMEmbeddings.ipynb

5_LazBCDEF.ipynb

6_DownstreamModelTraining.ipynb

7_tsne.ipynb

8_FineTuning.ipynb

9_Interpretation_650M.ipynb

10_interpretation_35M.ipynb

Figures.ipynb

OptionalDataPreprocessing.ipynb

PeptideESMTraining.ipynb
