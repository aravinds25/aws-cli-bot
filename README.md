# aws-cli-bot
A chatbot that helps you create AWS services.

This application uses IBM Watson for Natural Language Processing, and uses a Telegram bot as a front-end.
The Python module python-telegram-bot is used to get input from the bot interface, and the Python module watson-developer-cloud is used for sending messages to IBM Watson for parsing. 

The program takes in the Access Key and Secret Key as user input, and connects to their AWS account using the boto3 Python module. Once connected, users can create, stop, start, describe, or terminate EC2 instances.
