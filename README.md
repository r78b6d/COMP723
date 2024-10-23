java c
COMP723 Data Mining and Knowledge Engineering
Assignment  – Text Classification (S2, 2024)
1 Assignment Details Summary
Due Date: 27 October, midnight (/sunday of week 13)
Assignment group: To be done in Groups of 3
Submission: One copy from a pair, via Canvas.
Assignment Weight: 50%
2 Objective
To develop a broad understanding of text mining by performing a representative task, Text Classification.
3 Task SpecificationThe assignment requires classification of “free text” snippets into categories using machine learning algorithms.  You are required to use three different classification algorithms on the given two datasets, analyse the results, and present a report of your findings.
3.1 Due Dates and Submission
• This assignment should be done in groups of THREE.
• Only one person from the pair should submit the assignment.  The report should clearly state the name and student ID of the members of the team  as authors of the paper. Furthermore, the contributions made by each team member must be clearly stated in a section   named “Contributions – group    name” where    the    group   name    is “surname1/surname2/surname3”, at the beginning of the report.
• You are required to submit only an electronic copy of the assignment via the Turnitin assignment Submission tab (in the assignments tab) on the course page in Canvas.
3.2 Marking
•   This assignment will be marked out of 100 marks and is worth 50% of the overall mark for the paper.
4 Assignment Overview
The objective of the  assignment is to  do text classification using three machine learning algorithms on two datasets.
4.1 Dataset
The following datasets are to be used for the assignment.
1. Covid News Articles
2. Fake and Real News
3. Emotion Detection
4. Depression: Reddit Dataset
4.2 Dataset hosting
4.2.1 Directory Structure
In order to easily run the code for marking you are required to keep the data as zipped file in the following directory structure on your google drive with the specified filenames.
/content/drive/MyDrive/COMP723Data/Covid.zip
/content/drive/MyDrive/COMP723Data/Emotion.zip
/content/drive/MyDrive/COMP723Data/FakeReal.zip
/content/drive/MyDrive/COMP723Data/Depression.zip
4.2.2 Drive Mounting Code
You should include the following drive mounting code as the first cell of your script.
from google.colab import drive
drive.mount('/content/drive')
4.2.3 Sample Code for reading the zip file
Use the following sample code to read the zip file into a pandas dataframe.
import pandas as pd
import zipfile
zf = zipfile.ZipFile('/content/drive/MyDrive/COMP723Data/Covid.zip')
df = pd.read_csv(zf.open ('covid_articles_raw.csv'))
5 Assignment Tasks
1.   Read about the 4 datasets and choose 2 that you want to use for this assignment.
2.   Either download the 2 datasets from the sites directly (and rename them accordingly), or from Canvas assignment package. If the dataset doesn’t give you training and test sets, then do a stratified 80/20 train/test split of the dataset.
3.   The objective of this assignment is to compare the performance of three classification algorithms for the task of text classification. You will compare two given algorithms below, and the third one will be of your choice. The two algorithms are:
a)  Naïve Bayes
b)  Neural Network
c)  Your  choice.  Some  examples  are  SVM,  CRF,  J45,  a  variation  of Neural Network such as CNN, RNN, etc.
4.   Implement each of the 3 algorithms to train a model with the 2 datasets as Google Colab files, a separate file for each dataset. Ensure that you thoroughly document your code.
5.   Fine tune your algorithms by varying the parameter values to obtain the best possible results for each of the two datasets.
6.   Tabulate  your  results  using  Precision,  Recall  and  F1  value  relative  to  a  chosen category for the dataset.
7.  Now we want to try to代 写COMP723 Data Mining and Knowledge Engineering Assignment – Text Classification (S2, 2024)R
代做程序编程语言 further improve the results by pre-processing the datasets for noise and/or features. Experiment with a combination of the pre-processing tasks, to build features to be used for the two machine learning algorithms. They should be consistent for the three algorithms.
Some of the pre-processing you can use are :
a)   Stop word processing
b)  Stemming/lemmatization
c)   Feature size
d)  Type of vectorisationGenerate 2 well documented Google Colab files for each of the 2 datasets, each file containing  training  for  the  3  algorithms.  Tabulate  your  results  appropriately  to communicate your results from this task.
8. For submission you should have the 4 files and names (each file containing code for 3 algorithms:
a) Dataset_”name of dataset 1”.ipynb b)Dataset_”name of dataset 2”.ipynb
c) Dataset_”name of dataset 1”_preprocessed.ipynb
d)Dataset_”name of dataset 2”_preprocessed.ipynb
Ensure that you check the access to your file before submission. Also ensure that you save the results of your last run in the Colab before submission.
6 Written Report
• You will write a minimum of 6 and a maximum of 12 page report (excluding the references and appendix) describing the results of your experiment. You should write a  conference  publication   style. (single  column)  coherent  paper  with   appropriate academic language and referencing.
• The report should be a single pdf file containing the following:
• The report should include the following components.
1.   Abstract
•  What the paper is about.
2.   Introduction
• You  should  first  describe  the  task  of  text  classification  and  how  it  is similar/different to numerical data classification tasks.
• You   should   then   describe   the   purpose   of  the   experiments   and   the algorithms.  Include  overview  about  the  algorithms  used  and  the  main differences/similarities between them.
3.   Methodology
•   Description of how the experiments were done.
4.   Data Description
•   Metadata about the data
•   Properties of the data.
•   You  should  describe  the  datasets,  the  sources  and  all  aspects  of the datasets for the reader to be able to understand everything about the data.
3. Experiments
•   Describe each of the experiments in detail, done as described in Section
5 above. Your description should be such that it explains the rationale for doing the tasks and should include enough detail so that the reader should be able to recreate your experiments.
4. Results and Discussion
•   Include links to the code files for each of the experiments. Verify that the links work and the reader would be able to run the code by just clicking them.
•   In    this     section    appropriately     tabulate    all     your    results    and discussions/analysis of all the results. Include:
a) Any high/low Precision/Recall values.
b) Variations between the algorithms.
c) Any consistent patterns in results across the algorithms and/or datasets.
d) Any aberrations in results.
e) Anything that particularly worked well or not well at all.
f) Any other results that’s worth pointing out to the reader that came out of the experiments.
g) The best algorithm and pre-processing for the datasets.
5. Conclusion and Reflections
•   Describe which algorithms are appropriate for which type of datasets to get  the  best  possible  results.  Which  of  the  pre-processing  tasks  are effective and perhaps include computation times for training as well.
•   What would you do different if you were to do the whole project again. What did you do well?
7 Marking Scheme
The following approximate matrix would be used to grade your assignment.Written Report
Formatting, Language, Presentation, References5Introduction10Data Description10Experiments25Results and Discussion30Conclusion and Reflections5Code15Total100



         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
