# Django ReactJS Hello World

A simple Hello World project for learning how to integrate Django and ReactJS.

Based on the "[Django & React - Full Stack Web App Tutorial](https://www.youtube.com/watch?v=JD-age0BPVo&list=PLzMcBGfZo4-kCLWnGmK0jUBmGLaJxvi4j)" series from Tech With Tim.

# Setup 

## Prerequisites

- Python
<!-- TODO: - npm -->

## Visual Studio Code

It's recommended these extensions are installed:

- Python (id: ms-python.python)
- Django (id: batisteo.vscode-django)
- ES7 React/Redux/GraphQL/React-Native snippets (id: dsznajder.es7-react-js-snippets)
- JavaScript (ES6) code snippets (id: xabikos.javascriptsnippets)
- Prettier - Code formatter (id: esbenp.prettier-vscode)

## Virtual Envirnonment

Using a virutal environment is recommended.

`python -m venv venv`

`venv\Scripts\activate`

## Install Packages

The required packages are in the requirements.txt file.

`pip install -r requirements.txt`

# Running the Application

1. Navigate to the base directory
2. Activate the virtual environment (explained in the Setup section).
3. Navigate to the directory with the [manage.py](manage.py) file.
4. Migrate: `python manage.py migrate`.
5. Run the sever: `python manage.py runserver`.
6. Navigate to [localhost:8000/api](http://localhost:8000/api).