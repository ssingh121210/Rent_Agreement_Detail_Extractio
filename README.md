Rental Agreement Data Extraction:

Libraries Used: Spacy, Numpy, Pandas, NLTK, py-docx, re, os.

Problem Statement:

The Training data contained 42 Rental Agreement and the task was to extract certain information from those Agreement and cover them into a CSV file with Filename
and the given Entities: 
* Agreement Value 
* Agreement Start Date      
* Agreement End Date 
* Renewal Notice (Days) 
* Party One
* Party Two

Approach to the Problem:

1. As the given problem was of Name-Entity Recognition i used Spacy Library for extracting the entities from the text.
2. I merged the documents with the given Target values to form a single data frame.
3. After that I cleaned the given Rental agreement documents.
4. As the data had a lot of inconsistencies I had to manually find out the positions of various entities in the data.
5. After extracting the positions and entities for 10 documents, I trained the spacy model on those entities and document set.
