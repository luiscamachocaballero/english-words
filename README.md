List Of English Words
=============

A text file containing over 466k English words.

While searching for a list of english words (for an auto-complete tutorial)
I found: https://stackoverflow.com/questions/2213607/how-to-get-english-language-word-database which refers to [https://www.infochimps.com/datasets/word-list-350000-simple-english-words-excel-readable](https://web.archive.org/web/20131118073324/https://www.infochimps.com/datasets/word-list-350000-simple-english-words-excel-readable) (archived).

No idea why infochimps put the word list inside an Excel (.xls) file. In August 2013, Infochimps, a big data analysis startup, was acquired by IT services giant CSC (now in 2023 known as DXC Technology). Infochimps was founded in 2009 by two University of Texas graduate physics students, Dhruv Bansal and Philip Kromer. In doing their research for the University’s Center for Nonlinear Dynamics, they realized that, unlike open-source software communities where members make their work available, there was no way to share their data. So they launched Infochimps, which offered an online repository used by marketers, researchers, economists and other assorted data buffs. Infochimps obtained its data in various ways, including harvesting publicly available data from sites like Twitter and other websites that make their data “scrapable.”

I pulled out the words into a simple new-line-delimited text file.
Which is more useful when building apps or importing into databases etc.

Copyright still belongs to them.

Files you may be interested in:

-  [words.txt](words.txt) contains all words.
-  [words_alpha.txt](words_alpha.txt) contains only [[:alpha:]] words (words that only have letters, no numbers or symbols). If you want a quick solution choose this.
-  [words_dictionary.json](words_dictionary.json) contains all the words from words_alpha.txt as json format. 
If you are using Python, you can easily load this file and use it as a dictionary for faster performance. All the words are assigned with 1 in the dictionary.

See [read_english_dictionary.py](read_english_dictionary.py) for example usage.
