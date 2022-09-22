# Movie Recommendation from Conversational Data: ConvExtr
Re-implementation and extension of the ACL paper [You Sound Like Someone Who Watches Drama Movies: Towards Predicting Movie Preferences from Conversational Interactions](https://aclanthology.org/2021.naacl-main.246/)

-----------------------------------------
### Work Done

* Built a movie recommendation system leveraging user conversational data (transcripts), critics data and domain adaptation techniques
* Obtained a 3% improvement on existing results of the paper and performed hyperparameter tuning on all the three CF approaches: KNN, SVD and SVDpp.
* Experimented with neural matrix factorization approaches as an extension of the paper and obtained comparable results of RMSE=1.232 and MAE=0.9569. 

***

### Tech Stack

* Python 3
* surprise
* Microsoft Recommenders Framework
* seaborn

***

### Report and Presentation 

You can access the report [here](https://github.com/kunjmehta/movie-rec-conversational-data/blob/main/NLP_Final_Report.pdf) and presentation [here.](https://github.com/kunjmehta/movie-rec-conversational-data/blob/main/NLP-Final-Presentation.pptx.pdf)

### Structure and Acknowledgements 
The file "NLP_Project_Step1.ipynb" contains code for the re-implementation and hyperparameter tuning to obtain results published in the paper. The file "NLP_Project_Step2.ipynb" also contains code where the NMF extension is applied.

Made as a team with [@janish-parikh](https://github.com/janish-parikh) and Jash Gaglani.
