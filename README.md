# Spam-Email-Detector

## Purpose:
This project demonstrates a spam email detection application using Gradio and a pre-trained Hugging Face text-to-text pipeline. The application allows users to input an email and receive a classification as either "spam" or "not spam."

## Main Files and Functions:
* **`main.py`:** Contains the main logic for loading the Hugging Face pipeline, defining the Gradio interface, and processing user input.
* **`predict.py`:** If the prediction logic is complex, it can be separated into a separate file for better organization.

## Hugging Face Text-to-Text Pipeline:
A pre-trained text-to-text model from Hugging Face is used to classify emails as spam or not spam. The pipeline takes the email text as input and returns a classification label and confidence score.

## How to Run the Code:
1. **Install Requirements:** Ensure you have the necessary libraries installed:
   ```bash
   pip install transformers gradio
   ```
2. **Clone the Repository:** Clone this repository to your local machine.
3. **Run the Application:** Execute the `main.py` script:
   ```bash
   python main.py
   ```
4. **Access the Interface:** A Gradio interface will open in your web browser. Paste an email into the text box and click the "Submit" button to get the classification result.

## Expected Output:
The Gradio interface will display the predicted label ("spam" or "not spam") and the corresponding confidence score.

## Running Hugging Face Project Page
 running on Hugging Face Spaces here: [Hugging Face Spam Email Detector](https://huggingface.co/spaces/RakanAlsheraiwi/Spam_Email_Detector).

## Video walking through the Python Notebook.
[Click here to Watch the video](https://drive.google.com/file/d/1IkXMdy0wsMt87r0W9Ae1P7TLg-owXXZB/view?usp=sharing)

