# CWB-2023-Hackathon-sample

Problem statement: AI Chat bot that can teach you Git and GitHub. Specialized service trained on the open source git-scm book and open source GitHub Docs data sets along with a recent stackoverflow archive to help you learn how to contribute to an open source project and how to use all elements of GitHub.
Hint: Bot Framework
Objective: Create a chat bot to help users learn the basics of Git and GitHub using Git SCM, GitHub Docs and Stackoverflow archives as data sources.

The code should create a simple Flask app that implements a chatbot using Azure Cognitive Services Language Understanding (LUIS) API. 
#Set up the FLASK app and configure it = sets up the app, specifies the name and oncfigures it using the 'form_object' method
#Set up LUIS client and credentials = environment variables are used to store the LUIS app ID and subscription key and use these to initialize the LUISRuntimeClient object
#Define the webhook URL = the URL that the chatbot will use to receive messages from users (Question here - what URL do I actually add here? Do I need to create a interface, publish it, generate a URL for accessing it and then add it here?)
#Define the main route for the chatbot = I use the '/' ropute. The chatbot should parse the message and use LUIS to detect the itnent and entities in the message, then handle the message based on the detected intent
- (Question here - this sample code only handles a single prompt, in this case ' create repository' but obviously I need the chatbot to handle alot more prompts than just 1. How do I create a chatbot that takes user's inputs and analzes the data sources against those prompts? Or, how do I train a AI model to scrape the data sources to define possible topics/prompts and integrates it into this code? 

Current problems:
Ln 3 Col 6: Import requests could not be resolved. 
Ln 4 Col 4: Import flask could not be resolved.
Ln 5 Col 6: Import azure cognitice services luis runtime could not be resolved.
Ln 6 Col 6: Import ms rest.atuhentication could not be resolved.
Ln 44 Col 16: Expected indented block.
- For the last one, I think I need to convert indentation to spaces or to tabs ?
