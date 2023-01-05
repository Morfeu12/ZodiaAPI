## Dependencies
You need to install:
* Python 3.10.*

>> You need to activate the environment, that is, define a source (the VENV we created to install all the necessary resources, in this case, Flask)

## Create the folder for the project and the VENV
(where the Python virtual environment is)

Linux/macOS
```
python3 -m venv venv
```

Windows
```
python -m venv venv
```

## Activate the environment
Linux/macOS
```
. venv/bin/activate
```

Windows
```
venv\Scripts\activate
```

## Install
```
pip install Flask
```

## Check installation
```
flask --version
```

OBS: Need cmd run admin mode

## Run Flask - on (venv)

```
flask --app main run
```
