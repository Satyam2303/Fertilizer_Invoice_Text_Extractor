


<h1>Repository for the project Provider Invoice Text Curation.<h1>

<h2> Description <h2> 
Created a model to extract meaningful information from provided bill image by,
1) extracting text from image using a OCR (optical character recognition) model like Pytesseract.
2) Creating a NLP model to extract information from text using Spacy’s NER (named entity recognition) model.
3) Use Regex expressions for extracting emails, phone numbers etc where it can be used
4) Convert the output into extractable form
5) Finally, export the data into json format for further use.

<h2>Techstack<h2>
Technologies we used to make this project are:

Pytesseract - OCR engine for OCR

Open CV - reading and manipulating image

Spacy - NLP library for NER model\n

JSON module - output the file in JSON format\n

Python - programming language
 
<h2>Input and Output<h2>
# Output for Phone and Email-

<img width="1436" alt="Home_page" src="https://github.com/Satyam2303/Fertilizer_Invoice_Text_Extractor/blob/9f085b52a77e261719229301f69d849b9e4b2033/input.jpeg">
<img width="1436" alt="Home_page" src="https://github.com/Satyam2303/Fertilizer_Invoice_Text_Extractor/blob/9f085b52a77e261719229301f69d849b9e4b2033/output1.png">

# Output for Fertilizer name-

<img width="1436" alt="Home_page" src="https://github.com/Satyam2303/Fertilizer_Invoice_Text_Extractor/blob/9f085b52a77e261719229301f69d849b9e4b2033/input2.jpeg">
<img width="1436" alt="Home_page" src="https://github.com/Satyam2303/Fertilizer_Invoice_Text_Extractor/blob/9f085b52a77e261719229301f69d849b9e4b2033/output2.png">
