Looking for a data science position at Facebook?  After two successful prior Kaggle competitions, Facebook continues their mission to identify the best data scientists and software engineers that Kaggle has to offer. In this third installment, they seek candidates who have experience text mining large amounts of data.

Tags

This competition tests your text skills on a large dataset from the Stack Exchange sites.  The task is to predict the tags (a.k.a. keywords, topics, summaries), given only the question text and its title. The dataset contains content from disparate stack exchange sites, containing a mix of both technical and non-technical questions.

Positions are available in Menlo Park, Seattle, New York City, and London; candidates must have, or be eligible to obtain, authorization to work in the US or UK.

Please note: you must compete as an individual in recruiting competitions. You may only use the data provided to make your predictions. Crawling stack exchange sites to look up answers is not permitted. Facebook will review the code of the top participants before deciding whether to offer an interview. 

This competition counts towards rankings & achievements.  If you wish to be considered for an interview at Facebook, check the box "Allow host to contact me" when you make your first entry.

Source : <a href="https://www.kaggle.com/competitions/facebook-recruiting-iii-keyword-extraction/overview"> Kaggle </a>

All of the data is in 2 files: Train and Test.

Train.csv contains 4 columns: Id,Title,Body,Tags

    Id - Unique identifier for each question
    Title - The question's title
    Body - The body of the question
    Tags - The tags associated with the question (all lowercase, should not contain tabs '\t' or ampersands '&')

Test.csv contains the same columns but without the Tags, which you are to predict.

The questions are randomized and contains a mix of verbose text sites as well as sites related to math and programming. The number of questions from each site may vary, and no filtering has been performed on the questions (such as closed questions).

Data can be found <a href="https://www.kaggle.com/competitions/facebook-recruiting-iii-keyword-extraction/data"> here. </a>
