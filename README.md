# TextAugmentor
A simple library that can augment text corpora for NLP problems

## Usage
Make sure you have the following libraries installed :
1. nltk
2. requests
3. BeautifulSoup4
4. lxml

## Example

'''
import TextAugmentor as ta
sentence = "Today the weather was really beautiful" #The sentence we want to augment
augmentor = ta.TextAugmentor(sentence) #Create a TextAugmentor object out of this sentence
augmentor.GenerateSentences() #Call the GenerateSentences() function on the object to augment the input sentence
'''
