# Natural-language-processing

<h2>Week - 1</h2>
Task : Choosen an english word, and see how it is used in the different sentences

Sample :
```notepad
Enter no of sentences : 3
sentence 1 : My name is
sentence 2 : name is
sentence 3 : My 

output : 

is : [1, 2]
My : [1, 3]
name : [1, 2]
```
<h2>Week - 2</h2>
Task - a : How many words are there in the given text file

Sample text file contents : 
```notepad
this is a sample text
from the nlp lab
```
Output :
```notepad
Enter file name / Path : Sample.txt
9
```
Task - b : How many different words are there in the given text

Sample : 
```notepad
Enter the statement : hi hello welcome hi hello
```
Output : 
```notepad
{'hi': 2, 'hello': 2, 'welcome': 1}
```
Task - c : How many times does the word occur in the text file

Sample text file contents : 
```notepad
this is a sample text
from the nlp lab
```
Output : 
```notepad
Enter the file name / file path : Sample.txt
Enter substring : this
this : 1
```
Task - d : What is the percentage of all the words in the text file

Sample :
```notepad
Enter no of statements : 4
Enter statement : statement one
Enter statement : statement two
Enter statement : statement three
Enter statement : statement four
```
Output : 
```notepad
four : 12.5 %
one : 12.5 %
statement : 50.0 %
three : 12.5 %
two : 12.5 %
```

<h2>Week - 3</h2>
Task : Spelling corrector

Sample input word : 
```notepad
appple
```
Output :
```notepad
apple
```
Sample input sentence : 
```notepad
languagee appplee
```
Output :
```notepad
language apple
```
<h2>Week - 4</h2>
Task : Performing tokenization, stemming and lemmatization to carry out the analysis with text corpus [ nltk.corpus.gutenberg -> dataset [ paragraphs ] ]

1.a. Word tokenization
<img src="https://smltar.com/diagram-files/tokenization-black-box.png">

1.b. Sentence tokenization
```notepad
hello good morning, Welcome to nlp lab. Today we are going to compile WEEK_3 programs.
```
Output : 
```notepad
['hello good morning, Welcome to nlp lab.',
 'Today we are going to compile WEEK_3 programs.']
```
2. stemming
<img src="https://qph.cf2.quoracdn.net/main-qimg-187b045c480fa7c0b16869daa0661b5a">

3. Lemmatisation 
<img src="https://global-uploads.webflow.com/5ef788f07804fb7d78a4127a/61cabe3ac8046f4ca17b01d5_lemmatization.jpeg">

<h2>Week - 5</h2>
Task : To remove the stop words from the sentence

Stopwords : 
```notepad
['i', 'me', 'my', 'myself', 'we', 'our', 'ours', 'ourselves', 'you', "you're", "you've", "you'll", "you'd", 'your', 'yours', 'yourself', 'yourselves', 'he', 'him', 'his', 'himself', 'she', "she's", 'her', 'hers', 'herself', 'it', "it's", 'its', 'itself', 'they', 'them', 'their', 'theirs', 'themselves', 'what', 'which', 'who', 'whom', 'this', 'that', "that'll", 'these', 'those', 'am', 'is', 'are', 'was', 'were', 'be', 'been', 'being', 'have', 'has', 'had', 'having', 'do', 'does', 'did', 'doing', 'a', 'an', 'the', 'and', 'but', 'if', 'or', 'because', 'as', 'until', 'while', 'of', 'at', 'by', 'for', 'with', 'about', 'against', 'between', 'into', 'through', 'during', 'before', 'after', 'above', 'below', 'to', 'from', 'up', 'down', 'in', 'out', 'on', 'off', 'over', 'under', 'again', 'further', 'then', 'once', 'here', 'there', 'when', 'where', 'why', 'how', 'all', 'any', 'both', 'each', 'few', 'more', 'most', 'other', 'some', 'such', 'no', 'nor', 'not', 'only', 'own', 'same', 'so', 'than', 'too', 'very', 's', 't', 'can', 'will', 'just', 'don', "don't", 'should', "should've", 'now', 'd', 'll', 'm', 'o', 're', 've', 'y', 'ain', 'aren', "aren't", 'couldn', "couldn't", 'didn', "didn't", 'doesn', "doesn't", 'hadn', "hadn't", 'hasn', "hasn't", 'haven', "haven't", 'isn', "isn't", 'ma', 'mightn', "mightn't", 'mustn', "mustn't", 'needn', "needn't", 'shan', "shan't", 'shouldn', "shouldn't", 'wasn', "wasn't", 'weren', "weren't", 'won', "won't", 'wouldn', "wouldn't"]
```

Text with no stopwords : 

<img src="https://www.flexxcreative.com/wp-content/uploads/2017/06/stop-words-list.jpg">
