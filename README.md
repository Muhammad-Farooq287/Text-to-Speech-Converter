# Text-to-Speech-Converter
#It is a Simple program to convert any text to speech in any language using Python Programming Language For Windows.
#Install gTTS package using pip
!pip install gTTS

#Import gTTS
from gtts import gTTS
import os

#Text to be converted to speech
mytext = 'Hi Commando! Its Programmer Here.'

#Language to be converted in
language = 'en'
myobj=gTTS(text=mytext, lang=language)

#Saving Converted Audio
myobj.save('Text to Speech using Python.mp3')
#Now, Move to the folder where you've saved the mp3 file and run it. 

#To Run File
os.system("Text to speech using Python.mp3")
