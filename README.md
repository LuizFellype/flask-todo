# Todo

A simple todo-list web application which provides the following functionality:  
• A list of todos  
• Create a new todo item  
• Mark a todo item as done or undone  
• Edit a todo item  
• Delete a todo item  
• Mark everything as completed  

The project makes use of Python3, Flask, SQLite, Bootstrap and JQuery.

## Getting Started

git clone git@github.com:LuizFellype/Flask-ToDo-List.git && cd flask-todo

##### Create virtualenv and activate
python3 -m virtualenv venv
source venv/bin/activate

##### Install deps and run project
pip3 install -r requirements.txt

export FLASK_APP=app.py  
flask run  #flask run --host=0.0.0.0 (if require server to be publicly accessible)  

Navigate to: http://localhost:5000/

## Authors

**Zac Clery**

## License

This project is licensed under the MIT License
