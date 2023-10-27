The dataset consists of three CSV files: 
- Question_data.csv
- PyResponses.csv and
- MLResponses.csv.

The data description of  "Question_data.csv":
- QuestionID: Each question is assigned a unique identifier with the data type as Object.
- QuestionText: The actual questions for which students are required to provide answers.
- QuestionType: This is a categorical column that can take values such as Remember, Define, Difference, Explain, or Apply.
- ReferenceAnswer: The answer provided by the Subject Matter Expert (SME) for the corresponding QuestionText.

The files "PyResponses.csv" and "MLResponses.csv" contain student responses collected from examiners. The data columns in these files include:
- QuestionID: The identifier for the question to which the student response corresponds.
- StudentAnswer: The text written by students in response to the question.
- Score1: A discrete value ranging from 0 to 5, assigned by human annotator 1.
- Score2: A discrete value ranging from 0 to 5, assigned by human annotator 2.




