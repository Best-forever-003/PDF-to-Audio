# PDF-to-Audio

Being a college student, I have become lazy to take notes reading the PDF. So, I decided to program a model that reads out the PDF for me.

As my model reads the PDF, I shall note down the important points for my exam. 

Let us dive into our model,

I have used Pycharm as my IDE and launched Python 3.10.1 as my latest version.

I have created my project file and installed the necessary packages for the environment. I imported two libraries pip install pyttsx3 and pip install PyPDF2. 

pyttsx3 means text to speech. 
pip install means to install a package.

Upload your PDF in the folder of your file manager, where the model was saved.

book = open(' type the PDF name .pdf', 'rb') 

rb means read-only in binary format.

PyPDF2 is a pure-python PDF library capable of splitting, merging together, cropping, and transforming the pages of PDF files

PdfFileReader provides a method getFormTextFields() to extract text data from the interactive PDF in Python.

pdfreader.numpages to get the number of pages

Let us print the PDF to make the speaker of our project read.

init is for initialisation purpose.

getpage is used to tell the speaker which page to read.

page.extractText() we are extracting the text alone. 

speaker.say(text) converts text to speech.

speaker.runAndWait() - This makes the audio audible 


So, I hope this project seems interesting! 
Thanks for reading!
Hope this helps you!
