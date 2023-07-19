# text-summarization-web-app

This is a Streamlit-based web application that allows users to summarize text and documents using the txtai library. This repository contains the code for this application.

## Requirements
1. Python 3.7 or higher
2. streamlit
3. txtai
4. PyPDF2
5. streamlit_lottie
6. requests

## Installation

1. Clone the repository to your local machine
2. Install the required libraries using the following command:

> pip install -r requirements.txt

## Usage

1. To run the application, use the following command:

> streamlit run app.py

2. After running the command, a web page will open in your default browser. From here, you can select whether to summarize text or document.
3. If you select "Summarize Text", paste your text in the input box and click on the "Summarize Text" button to get a summary of your text.
4. If you select "Summarize Document", upload your document in PDF format and click on the "Summarize Document" button to get a summary of your document.
Note: The web page layout is set to "wide" and the initial sidebar state is "expanded".

## Credits
This application uses the following libraries:

1. [Streamlit](https://streamlit.io/)
2. [txtai](https://github.com/neuml/txtai)
3. [PyPDF2](https://github.com/py-pdf/pypdf)
