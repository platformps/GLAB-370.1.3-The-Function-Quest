# Flask Quest: A Beginner's Guide to Building a Web App

## Description
In this lab, students will learn how to set up and run a basic Flask web application. They will create views and routes to handle user requests and learn about the benefits of using Flask for web development.

## Instructions
- [ ] Begin by introducing Flask and its benefits to the students.
- [ ] Have the students install Flask on their local machines using pip.
- [ ] Walk the students through the process of creating a basic Flask application with the following code:

```
from flask import Flask

app = Flask(__name__)

@app.route("/")
def home():
    return "Hello, World!"

if __name__ == "__main__":
    app.run(debug=True)

```

- [ ] Have the students explain what the code does and how it works.
- [ ] Explain how to define views in Flask and how to handle user requests using routes.
- [ ] Have the students create a new view and route that returns a different message.
- [ ] Have the students start the Flask application by running the app.run() command.
- [ ] Explain how to run a Flask application on a server and have the students run their application on a local server.
