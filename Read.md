# Project Title
```
Sonar Rock Vs Mine Prediction

Author(s): Snehal Wath
Affiliation:Suryodaya college / RTMNU
Date: 27/03/2026
```
## Abstract
```
This project is about checking plagiarism in online assignments. Plagiarism means copying content from other sources without permission.
We use machine learning and text comparison methods to find how much content is copied between two documents.
The system compares the given assignment with other sources and calculates similarity. Based on that, it tells whether the content is original or copied.
The main goal of this project is to help students and teachers maintain originality in assignments and improve academic honesty.
```

## Introduction
```
In colleges and schools, students submit assignments regularly. Sometimes students copy content from the internet or from other students.
This is called plagiarism and it is not allowed in academics. It affects learning and honesty.
So, there is a need for a system that can automatically check whether an assignment is copied or not.
In this project, we build an online plagiarism checker using machine learning and text analysis techniques.
This system helps teachers and students ensure that the content is original and fair.
```

##Literature review
```
Many plagiarism detection systems are already used in universities and online platforms.
Tools like Turnitin and Grammarly check similarity between documents.
Researchers use methods like cosine similarity, NLP techniques, and string matching to detect plagiarism.
Machine learning improves accuracy by understanding text patterns instead of just matching words.
This project is inspired by such tools and uses simple techniques to detect copied content.
```
## Methodology
```
First, we take the input assignment text from the user.
Then we preprocess the text by removing stop words, punctuation, and converting it into a simple format.
After that, we compare the text with other documents or a database of existing content.
We use similarity methods like cosine similarity or NLP techniques to check how much text matches.
Finally, the system gives a similarity score. Based on the score, it tells whether the assignment is original or plagiarized.
```

## Implementation
```
Programming Language: Python  
Libraries Used:  
- Pandas  
- NumPy  
- Scikit-learn  
- NLTK / SpaCy  
- TF-IDF Vectorizer  
Tools Used:  
- Jupyter Notebook / VS Code  
Steps followed:  
- Take input text from user  
- Preprocess the text  
- Convert text into numerical form using TF-IDF  
- Compare with existing documents  
- Calculate similarity score  
- Display result  
```

## Result and Discussion
```
The system successfully detects plagiarism in assignments.
It gives a similarity percentage that shows how much content is copied.
If the similarity is high, the assignment may be plagiarized.
This helps teachers easily identify copied work.
The system saves time and improves accuracy compared to manual checking.
```
## Limitation
```
1.It may not detect very smart paraphrased content  
2.Accuracy depends on the dataset used  
3.Requires a good database of existing content  
4.Sometimes it may give false results  
5.Complex sentences may reduce accuracy  
```

## Future Scope
```
1.Easy to use and automatic checking system  
2.Can detect copied content quickly  
3.Can be used in schools and colleges  
4.Can be improved with advanced AI models  
5.Can be developed into a web or mobile application  
6.Can support multiple file formats like PDF and Word  
```

## Conclusion
```
This project shows how plagiarism can be detected using simple machine learning techniques.
It helps maintain originality in assignments and improves academic honesty.
The system is fast and easy to use.
In future, it can be improved to detect more complex plagiarism and be used in real-time applications.
```
