To run this code:
Create a folder called PsychiaGPT in your base drive.
Download the entire git repo and extract the files into this folder.
There are 4 jupyter notebooks that should be run as Google Colabs that have all the runs. 

Finetuning BERT to classify is the original notebook used to build the BERT model. 
Copy of Fine Tuning GPT2 is the notebook used to train the GPT2 model.
Param tuning is a version of Finetuning Bert to classify that doesn't contain any of the fluff/instructions (i.e. much simpler to run)

At the bottom of every notebook, there are cells to save/load models from the folder model_save. Change and run these cells to load our models, and run the relevant cells to get our results.
