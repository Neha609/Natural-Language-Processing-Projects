# NLP-Exploring-Data

Problem Statement 1:

1) Take sample dataset of IMDB.
2) Remove special chracters and hyperlinks from text.
3) Using Spacy Find the user names,City mentioned in the top 5000 records
			 and store in list 
			 and add another column to list called Entity like 
			if name is name of person then new column should contain "Person"
		        if name is name of City then new column should be "City"
4) Store above data in DataFrame and convert  it to JSON and  return that JSON from function.
5) Create web app through Flask and create POST API and post API will take Name(text) as input parameter 
and should return is it City or Person.
