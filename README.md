My PDF Analyzer will take in a pdf from the user and provide key information about the pdf. 

Week 1

  This week I set up the basic user interface with spaces to display information about the pdf.
  I created a search pdf function where the user can search for a pdf on their computer for the program to read.
  There is an error function so if a pdf is not selected the program will ask for one.
  There is an "exit" button so the user can exit the program at any time.

Week 2

  This week I created functions to get information from the selcted pdf.
  The functions I created are get_title, get_word_count, get_key_topics, get_key_names and get_reading_level.
  Title is found through a library called PDFReader which can takes in a pdf and produce the title.
  Word count is found by breaking down the pdf into a list of words which the program counts.
  Key names are found through a library called "spacy" which has a function that recognizes names from a list of words.
  Reading level is found by taking the longest word in the pdf and comparing it to adverage reading levels.
  Key topics was found by taking a list of words from the pdf and filtering out stopwords and names. It then finds which words are most commonly used.
  Key topics is not perfect and is most effective when an article is read instead of a fictional book.

Week 3

  This week I created a serach function so the user can search their pdf for certain words.
  I added a search bar with a button for th user to input their search word.
  I displayed the results of the search and how often the word appears in the pdf.
  I added a border around the diaplayed results and the previous displayed text.
  I also centered the results and the title.
  I increased the size of the title so it's displayed clearly at the top of the page.
