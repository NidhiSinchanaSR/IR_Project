# IR_Project
Multilingual Detection of Hate Speech Against Immigrants and Women in Twitter:

Hate Speech is commonly defined as any communication that disparages a person or a group on the basis of some characteristic such as race, color, ethnicity, gender, sexual orientation, nationality, religion, or other characteristics. Given the huge amount of user-generated contents on the Web, and in particular on social media, the problem of detecting, and therefore possibly limit the Hate Speech diffusion, is becoming fundamental.
There is a paper that describes the organization of the SemEval 2019 Task 5 about the detection of hate speech against immigrants and women in Spanish and English messages extracted from Twitter. The task is organized in two related classification subtasks: a main binary subtask for detecting the presence of hate speech, and a finer-grained one devoted to identifying further features in hateful contents such as the aggressive attitude and the target harassed, to distinguish if the incitement is against an individual rather than a group
The proposed task consists in Hate Speech detection in Twitter but featured by two specific different targets, immigrants and women, in a multilingual perspective, for Spanish and English.

Data:
HatEval Dataset link: https://github.com/msang/hateval
HatEval consists in detecting hateful contents in social media texts, specifically in Twitter’s posts, against two targets: immigrants and women. Moreover, the task implements a multilingual per- spective where data for two widespread languages, English and Spanish, are provided for training and testing participant systems.
The file consists the following as its columns:
Id, Text, and categories such as HS, TR, AG  
HS - a binary value indicating if HS is occurring against one of the given targets (women or immigrants): 1 if occurs, 0 if not.
Target Range(TR)- if HS occurs (i.e. the value for the feature HS is 1), a binary value indicating if the target is a generic group of people (0) or a specific individual (1).
Aggressiveness(AG) - if HS occurs (i.e. the value for the feature HS is 1), a binary value indicating if the tweeter is aggressive (1) or not (0).

Code:
Firsly after loaing the dataset, the text is preprocessed.
Then vectors of the text is created; 2 kinds of vector, tfidf and Word2Vec vectors are created.
Then it is trained an tested using various models like Logistic Regression, KNN, etc.

How to run the code:
1.Upload all the files of the dataset
2.Install all the necessary packages mentioned in the code
3.Run each block of the code.


