https://raw.githubusercontent.com/laxmimerit/All-CSV-ML-Data-Files-Download/master/twitter_sentiment.csv
it is the link of the dataset. In this Repo we will learn file loading , word count , character count, average word length and stopwords etc.


word count: len('my name is shiblu das'.split())
this line count the number of word in a line. 

Char count: char_count() function count the number of character in a string. 

Avg length: num of char / num of word .
#characterLen/WordLen
x = 'this is' # 6/2 = 3

y = 'thank you guys'  #12/2 = 6

Stopwords : stopwords are the words which is used most in any language. 

Count Hash tag:  [t for t in x.split() if t.startswith('#')] this line try to find the word which starts with # . and put them in a list.

check_digits: st.isdigit() check that the character is a digit or not .
[t for t in x.split() if t.isdigit()] this itarate  all the word and check it's digit or not 

TextBlob(x).words ,, here x contain a string line. this function will remove all kind of special character in x and keep the actual character. 

doc = nlp(x)
for noun in doc.noun_chunks:
    print(noun)

here x is string . doc.noun_chunks will find all the noun from x.
    


