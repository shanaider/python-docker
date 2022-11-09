##setup
```
cd /path/to/python-docker
python3 -m venv .venv
source .venv/bin/activate
(.venv) $ python3 -m pip install Flask
(.venv) $ python3 -m pip freeze > requirements.txt
(.venv) $ touch app.py
```


##test
```
cd /path/to/python-docker
source .venv/bin/activate
(.venv) $ python3 -m flask run
```

ref. https://docs.docker.com/language/python/build-images/
