# Information-Extraction
The purpose of this project is to implement a template-based Information Extraction Application, that will extract predefined properties in a sentence by identifying the corresponding template. In this project, a rule-based strategy using various natural language features is used to achieve the task. 
This project has 4 tasks to be implemented.


Task 1: Creating templates for Information Extraction.


Task 2: Creating training corpus of natural language statements.


Task 3: Implementation of NLP pipeline to extract the below features.

a)	Tokenization of the sentences and words.

b)	Lemmatizing the words to extract Lemmas as features.

c)	POS tagging the words to extract POS tag features.

d)	Dependency parsing to parse-tree based patterns as features.

e)	Named Entity Recognition to identify the Named Entities in the sentence.
f)	Extracting synonyms, hypernyms, hyponyms, meronyms, and holonyms as features.


Task 4: Implementation of the rule-based strategy to fill the templates from the corpus of natural language statements.

Input:  
1.	Set of information templates 


Examples: 

•	Template #1:  KILLS(Killer, Victim, Date, Location) 

•	Template #2:  BORN(Person, Parents, Date, Location) 


2.	Set of natural language statements 


Examples:  

•	Statements 1:  Rohit killed Virat on 30th April 1987 in Dallas, Texas

•	Statements 2: Roddick was born the youngest of three boys in Omaha, Nebraska, the son of Blanche (née Corell), a school teacher, and Jerry Roddick, a businessman, on 30 April 1987
Output: Filled information templates 


Examples: 

•	Template #1: 
KILLS(“Rohit”, “Virat”, “30th April 1987”, “Dallas, Texas”) 


•	Template #2: 
BORN(“Roddick”, “Jerry Roddick”, “30 April 1987”, “Omaha, Nebraska”)
