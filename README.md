# Chat with PDFs using Google Gemini Pro

Google gemini Pro Chat PDF is a project that allows you to chat with PDF files using Gemini, a generative AI model from Google. You can upload your PDF files, ask questions about them, and get answers from the model.
You can also see the most similar documents to your query from the uploaded PDF files.

## Installation

* To install Chat PDF, you need to have Python 3.7 or higher and pip installed on your system. You also need to have a Google API key to use Gemini. You can get one from [here](https://deepmind.google/technologies/gemini/#build-with-gemini).

* Clone the repo :
  ```
  https://github.com/Swam80/LLM_GoogleGeminiPro_ChatPdf.git
  ```
  
* To install the required dependencies, run the following command in your terminal:

```bash
pip install -r requirements.txt
```

* To run Chat PDF, you need to set your Google API key as an environment variable in a .env file. Create a file named .env in the root directory of the project and add the following line:

```
GOOGLE_API_KEY=your_api_key
```
* Then, run the following command in your terminal:
```
streamlit run app.py
```

## Here is the UI.
![UI](https://github.com/Swam80/LLM_GoogleGeminiPro_ChatPdf/assets/42047546/5cc1ef3a-b4aa-43f0-920f-4ba8e1d4f32e)

## Shortcomings and Potential Improvments.
* Restricted to the contents of the pdf as it may not work well with general questions. Maybe with a more powerful LLM model and domain specific prompt it can do well.
* It would be interesting to check if we can integrate a functionality to analyze images within the pdfs.

## Credits
This project has been guided by Krish Naik [Here is the youtube link](https://www.youtube.com/@krishnaik06). He is a data scientist and an educator who has inspired many people to pursue this field.
