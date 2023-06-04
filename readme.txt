[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black) 
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)

**main.py** is a simple application for creating day-tasks and putting them into a list using json-server. 

## Installation

Cloning, installing, and running Hyde is as simple as executing the following commands:

##### Step 1: clone the repo
```
git@github.com:Nadezhda-Klementionok/todolist.git
```

##### Step 2: setup node.js
 - https://nodejs.org/en/download

##### Step 3: Install JSON Server
```
npm install -g json-server
```

## Documentation

```
python -m pydoc .\main.py
```

## Supported Features
1 - show_json_and_dict() - 
Function for displaying the contents of the day_tasks file.json in the form of json and a dictionary.
2 - task_get() is a function for displaying tasks in the day_tasks.json file sorted by priority.
3 - task_get_id() - task output function based on the entered id.
4 - task_delete() - The task deletion function by the entered id.
5 - task_post() - Function for adding a new task to day_tasks.
6 - task_put() - Function for changing task to day_tasks.


## Running the app

Cloning, installing, and running Hyde is as simple as executing the following commands:

##### Step 1: Start JSON Server
```
json-server --watch day_tasks.json
```
##### Step 2: Run the main app
```
py main.py
```

## Contributing

kayat_n@tut.by
