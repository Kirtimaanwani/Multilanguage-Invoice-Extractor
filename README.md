# Gemini Image Invoice Extractor

## Overview

The **Gemini Image Invoice Extractor** is a Streamlit application that leverages Google's Gemini Generative AI to analyze and extract information from invoices in images. The application allows users to upload images of invoices and enter prompts to receive answers based on the content of the invoice.

## Features

- **Image Upload**: Upload images in JPEG, PNG, or JPG format.
- **Generative AI Integration**: Utilizes Google's Gemini Generative AI to process and analyze invoice images.
- **Interactive Q&A**: Enter prompts to ask questions about the invoice content.
- **User-Friendly Interface**: Built with Streamlit for a seamless user experience.

## Prerequisites

Before you begin, ensure you have the following installed:

- Python 3.10 or higher
- [Streamlit](https://docs.streamlit.io/library/get-started)
- [Google Generative AI](https://developers.google.com/generative-ai)
- [python-dotenv](https://pypi.org/project/python-dotenv/)
- [Pillow](https://pillow.readthedocs.io/en/stable/)
  
You can install the required Python packages using pip:

```bash
pip install -r requirements.txt
```

## Getting Started

    Clone the Repository

   
```
git clone https://github.com/your-username/gemini-invoice-extractor.git
cd gemini-invoice-extractor
```
**Set Up Environment Variables**

Create a .env file in the root directory of the project and add your Google API key:

dotenv
```
GOOGLE_API_KEY=your_google_api_key_here
```
Run the Application

Launch the Streamlit app with:

```
streamlit run app.py
```
Replace app.py with the name of your Python script if it's different.

Access the App
```
Open your web browser and navigate to http://localhost:8501 to use the application.
```
Usage

   - Upload an Image: Click the "Choose an image..." button to upload an invoice image.
   - Enter a Prompt: Type a question related to the invoice content in the input field.
   - Submit: Click "Tell me about the image" to receive a response from the AI based on the provided image and prompt.

Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.
License

This project is licensed under the MIT License - see the LICENSE file for details.
Acknowledgments

    Google Gemini for the generative AI model.
    Streamlit for the easy-to-use web framework.
    Pillow for image processing.

Contact

For any questions or feedback, please contact biggerbody005@gmail.com
