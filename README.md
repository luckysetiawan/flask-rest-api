# Flask Rest API

Video sharing platform REST-API using flask

# Setup

## Virtual Environment

### Create a new Virtual Environment
```
python -m venv flask-rest-api
```

### Activate the Virtual Environment
```
flask-rest-api\scripts\activate
```
If you're on Microsoft Windows, you may encounter an error like the following:

`\Scripts\Activate.ps1 cannot be loaded because running scripts is 
disabled on this system.`

According to the [official Python documentation](https://docs.python.org/3/library/venv.html), to fix that simply use the command below before activating the virtual environment.
```
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
```

## Install Dependencies

### Using requirements.txt
```
pip install -r requirements.txt
```

# Credits

Source code was written with the guidance from [Tech With Tim](https://youtu.be/xqJXDZvtogY).