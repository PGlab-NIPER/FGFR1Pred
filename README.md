# FGFR1Pred
FGFR1Pred: A random forest-based model to predict fibroblast growth factor receptor1 inhibitors

Instructions: 
1. Install R language and make sure to add the path of R language to the system environment variables. If R version 4.1.1 is installed, then the following command can be used to add R language to system environment variables:

`pathman /au C:\Program Files\R\R-4.1.1\bin\x64\`

Change this command according R version installed by the user


2. Install required R packages by executing following command:

`R -e "install.packages(c('randomForest','caret'),repos='https://cloud.r-project.org', dependencies=TRUE)"`


3. Download this github repository in single folder.


4. Save all the query molecules as .smi file named as inputmols.smi in the inputmols folder.


5. Then use the following command to make the prediction.

`Rscript prediction_program.R`


6. Once the command is processed, the results will be saved in the Results folder as .csv file.

