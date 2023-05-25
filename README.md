# Frankenstein
For this project, you'll write your own program from scratch where you pick one classic novel and analyze it by:
	How many words 
	How many unique words 
	How often the most used words accur in the novel
Pick a novel from https://www.gutenberg.org/. Download the plain text file.
Tip:
To open a file you have to add the encoding parameter:
f = open( 'filename.txt', encoding="utf8" ) 


Requirements for your project:
Your program must include:

	load the file with the novel into your python program and save its content into a variable
	make sure words are not counted as new words if they have a comma, point, etc, attached to them or if they are lower or upper case
		replace commas, points etc, with white spaces
		transform the string to all lower case
	tokenize the string
	Count the number of words and unique words and print a sentence with the results.
	count how often each word occurs using a for loop and save the result in a dictionary
	print the result in a table for the most occuring words
		Only show results for the roughly 30 most appearing words, for example if the word appears at least 100 (it depends on your novel which value you use) 
			times in the novel.
		The table needs to look somewhat pretty: all entries for a given column start aligned under each other and add a headline
			documentation of the programming code
	Create a visualization (you can choose which type) which shows how often the most ten occuring words appeared in the novel
		add a meningful title to the diagram which also contains the title of the novel
