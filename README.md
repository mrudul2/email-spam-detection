# email-spam-detection

Spam Detector
This project aims to detect whether a given text is spam or not. The user can enter any text in the input field, and the system will analyze it to determine if it is spam. This project uses a simple web interface that allows the user to enter text and get an immediate response.

Usage
Open the index.html file in your browser
Enter the text you want to check for spam
Click the "Check Spam" button
The system will analyze the text and determine whether it is spam or not

How it works
The Spam Detector system analyzes the input text using a machine learning model that has been trained on a large dataset of spam and non-spam messages. The model uses a combination of natural language processing techniques and statistical analysis to determine whether the input text is spam or not.

The system makes a request to a backend server using the fetch API. The server receives the text as a JSON object, and returns a response with a is_spam field set to either 1 (for spam) or 0 (for not spam). The response is then parsed by the client-side JavaScript code and an appropriate message is displayed to the user

