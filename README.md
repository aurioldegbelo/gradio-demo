# gradio-demo

Simple demo to play around with gradio as an application. 

To start:
* create a virtual environment, e.g. ```python -m venv my-envi ```
* activate the environment, e.g.  ```source my-envi/bin/activate ```
* install the necessary libraries to run your code (in this case, you would need
  - ```pip install spacy gradio ```
  - ```python -m spacy download en_core_web_sm ```
* run your application using ```python app.py ```
* export the requirements using ```pip freeze > requirements.txt ```

The app.py and requirements.txt files can then be used to deploy the application on [Hugging Face](https://huggingface.co/spaces/aurioldegbelo/ner_space_2023/tree/main).
