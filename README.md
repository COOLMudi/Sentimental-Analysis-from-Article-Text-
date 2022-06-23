# Sentimental-Analysis-from-Article-Text-
Sentimental analysis is the process of determining whether a piece of writing is positive,
negative or neutral. The below Algorithm is designed for use on Financial Texts. It consists
of steps:
1. Cleaning using Stop Words Lists
2.  Creating dictionary of Positive and Negative words
3.  Extracting Derived variables
>>We convert the text into a list of tokens using the nltk tokenize module and use these tokens to calculate the 4 variables described below:
>> ---------------------------------------------------------------------------------------
>>Positive Score: This score is calculated by assigning the value of +1 for each word if found in the Positive Dictionary and then adding up all the values.
>> ---------------------------------------------------------------------------------------
>>''Negative Score: This score is calculated by assigning the value of -1 for each word if found in the Negative Dictionary and then adding up all the values. We multiply the score with -1 so that the score is a positive number.''
>> ---------------------------------------------------------------------------------------
>>Polarity Score: This is the score that determines if a given text is positive or negative in nature. It is calculated by using the formula:
>>Polarity Score = (Positive Score – Negative Score)/ ((Positive Score + Negative Score) +0.000001)
---------------------------------------------------------------------------------------------------
>>Subjectivity Score: This is the score that determines if a given text is objective or subjective.It is calculated by using the formula:
>>Subjectivity Score = (Positive Score + Negative Score)/ ((Total Words after cleaning) +0.000001)

4. Analysis of Readability
5.  Average Number of Words Per Sentence
6. Complex Word Count (contain more than two syllables)
7. Personal Pronouns etc

## 🚀 About Me
Hola, mi nombre es Mudit 
I'm a Machine Learning and Data Science Enthusiast.
I am interested in Business Analytics and Market Research as well as Predictve Finance Analysis.
I am skilled in Python Language, SQL, C++, Data Science and ML , Data Visualisation and Keras/ Tensorflow, Stramlit and Analytics.
Do checkout my repo!!
Gracias :)
