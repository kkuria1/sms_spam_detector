SMS Spam Classifier

This project is an SMS Spam Classification tool that uses machine learning to classify SMS messages as “spam” or “not spam”. The project leverages a Linear Support Vector Classification (SVC) model combined with TF-IDF vectorization to identify spam messages. A Gradio web app interface is provided to allow users to input messages and see real-time classification results.

Features

	•	Spam Detection: Classifies SMS messages as “spam” or “not spam” based on text content.
	•	Machine Learning Pipeline: Uses TF-IDF vectorization and a Linear SVC model for classification.
	•	Interactive Web Interface: Built with Gradio, allowing users to test messages easily.

Installation

	1.	Clone the repository:

git clone https://github.com/yourusername/sms_spam_classifier.git
cd sms_spam_classifier


	2.	Install the required dependencies:

pip install -r requirements.txt



Usage

	1.	Train the Model:
Run the Jupyter Notebook (gradio_sms_text_classification.ipynb) to train the model on the SMS dataset (SMSSpamCollection.csv).
	2.	Launch the Gradio App:
Execute the following in the terminal or within the notebook to start the app:

iface.launch()


	3.	Test Messages:
Open the Gradio interface and input any SMS text to see if it’s classified as “spam” or “not spam”.

Example Messages

Here are a few messages to test:
	•	“You are a lucky winner of $5000!”
	•	“You won 2 free tickets to the Super Bowl.”
	•	“Thanks for registering. Text 4343 to receive free updates on Medicare.”

Project Structure

	•	gradio_sms_text_classification.ipynb: Main notebook that contains the SMS classification code and Gradio app setup.
	•	sms_text_classification_solution.ipynb: Original solution with code for the SVC model.
	•	SMSSpamCollection.csv: Dataset containing labeled SMS messages for training the model.

Requirements

	•	Python 3.7+
	•	scikit-learn
	•	pandas
	•	Gradio

Acknowledgments

This project is inspired by common machine learning practices for text classification and aims to demonstrate how ML can be used to detect SMS spam.

