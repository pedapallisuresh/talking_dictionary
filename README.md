# speaking_dictionary
This can be able to search the meaning of the text and read out.
The following article shows how by the use of two modules named, pyttsx3 and PyDictionary, we can make our system say out the meaning of the word given as input. It is module which speak the meaning when we want to have the meaning of the particular word.

Modules needed :
PyDictionary: It is a Dictionary Module for Python 2-3 to get meanings, translations, synonyms and Antonyms of words. It uses WordNet for doing as its functionality suggests and has dependencies on modules named Requests, BeautifulSoup4 and goslate .
pyttsx3: It is a text to speech library. This module is what gives our system voice so that they can communicate with us. Pyttsx3 uses sapi5 in windows and espeak in windows.
Both modules can be installed by using pip in the following way:

pip install PyDictionary
pip install pyttsx3  
Working
As mentioned above, by the combination of two modules we will generate the functionality required and to do that the following steps were taken:

A method is defined to make the system search for the meaning of the word provided as input
Another method is defined to make the system say out loud the output generated corresponding to the input provided.
The output returned in this may be a dictionary, so we have to extract each meaning of the word provided as it will be in a key-value format.
