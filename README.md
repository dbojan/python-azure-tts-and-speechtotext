# python-azure-tts-and-speechtotext
#2024-05-18-1/2024-05-18-1

Using azure from python for 'text to speech' and 'speech to text'  
You can use azure for free for 12 months, after that you have to pay.
You **must move to pay as you go (basic supscription - $0) after first month.** Be careful not to go over free amount of units.  
More info here: https://github.com/dbojan/python-azure-ocr/

## setting azure
you need phone number (not virtual), and credit card which will not be charged (shouldn't be for free tier, except may 1$ which will be paid back...)  
https://portal.azure.com/#home

select 'speech services' on the left  
click on +  
select location (for example north europ), free tier (f0), enter new name for resources  

when you are done click on **key and location**. you will need them later.


## using the program
download zip, enter your **key and location** in .py file. You can open .py using notepad++ or notepad.

install needed packages for python:  
pip install azure-cognitiveservices-speech

start bat file  
programs will use 1.wav (speech to text), or 1.txt (text to speech, utf-8 encoded preferred)

dll files are for windows 8.1 should not be needed on newer windows, like windows 10,11 ...
