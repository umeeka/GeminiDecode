# GeminiDecode: Multilanguage Document Extraction by Gemini Pro

GeminiDecode is a cutting-edge solution designed to extract and process data from documents in multiple languages with unparalleled efficiency. Leveraging advanced natural language processing (NLP) and machine learning algorithms, it seamlessly identifies, extracts, and categorizes information from diverse document formats, ensuring accuracy and speed. Ideal for global businesses, GeminiDecode supports over 50 languages, providing robust data extraction capabilities that streamline workflows, enhance productivity, and improve decision-making processes.

## Features
- **Multilanguage Support:** Extracts data from documents in over 50 languages.
- **Advanced NLP and ML:** Utilizes cutting-edge natural language processing and machine learning algorithms.
- **Efficiency and Accuracy:** Ensures high accuracy and speed in data extraction and processing.
- **Versatile Document Formats:** Supports diverse document formats.

## Project Flow

1. **User Interaction:** User interacts with the UI to enter the input.
2. **Data Transmission:** User input is collected from the UI and transmitted to the backend using the Google API key.
3. **Model Processing:** The input is forwarded to the Gemini Pro pre-trained model via an API call.
4. **Result Generation:** The Gemini Pro pre-trained model processes the input and generates the output.
5. **Output Display:** The results are returned to the frontend for formatting and display.

<img width="679" alt="Screenshot 2024-06-22 at 10 46 03 AM" src="https://github.com/karthiksagarN/GeminiDecode_SmartInternz/assets/111840048/1daf9efc-a4f4-41d8-8c45-7a6d80e39d7d">

## Requirements Specification

### Steps to Complete the Project

1. **Requirements Specification**

   Create a `requirements.txt` file to list the required libraries.Install the required libraries.
   Specifying the required libraries making it easier for others to replicate the development environment.

    - Streamlit:  Streamlit is a powerful framework for building interactive web applications with Python.
    - Streamlit_extras:  Additional utilities and enhancements for Streamlit applications.
    - Google-generativeai:  Python client library for accessing the GenerativeAI API, facilitating interactions with pre-trained language models like Gemini Pro.
    - Python-dotenv:  Python-dotenv allows you to manage environment variables stored in a .env file for your Python projects.
    - PyPDF2:  It is a Python library for extracting text and manipulating PDF documents.
    - Pillow:  Pillow is a Python Imaging Library (PIL) fork that adds support for opening, manipulating, and saving many different image file formats.
    - LangChain: Provides tools and abstractions to improve the customization, accuracy, and relevancy of the information the models generate
 

3. **Initialization of Google API Key**
    - Generate Google API Key.
    - Initialize Google API Key.

4. **Interfacing with Pre-trained Model**
    - Load the Gemini Pro pre-trained model.
    - Implement a function to get Gemini response.
    - Implement a function to read PDF content.
    - Write a prompt for Gemini model.

5. **Model Deployment**
    - Integrate with Web Framework.
    - Host the Application.

## Prior Knowledge Required

Its benificial to have prior knowledge of the following topics to complete this project:

- **Generative AI Concepts**
    - [NLP](https://www.tutorialspoint.com/natural_language_processing/index.htm)
    - [Generative AI](https://en.wikipedia.org/wiki/Generative_artificial_intelligence)
    - [About Gemini](https://deepmind.google/technologies/gemini/#introduction)
    - [Gemini API](https://ai.google.dev/gemini-api/docs/get-started/python)
    - [Gemini Demo](https://colab.research.google.com/github/google/generative-ai-docs/blob/main/site/en/gemini-api/docs/get-started/python.ipynb)
    - [Streamlit](https://www.geeksforgeeks.org/a-beginners-guide-to-streamlit/)

