[![Python 3.10.8](https://img.shields.io/badge/python-3.10.8-blue.svg)](https://www.python.org/downloads/release/python-3108/)
![app coverage](https://img.shields.io/badge/app_test_coverage-43%25-yellowgreen)

![ScreenShot](img/sound_logo.png)

### Usage
```shell
docker-compose up -d --build
```
### Frontend 
via [streamlit](https://github.com/streamlit) starts on http://0.0.0.0:8000

### Backend API Documentation: 
http://0.0.0.0:9090/docs

### Development
Install dev environment:
```shell
pip install -r app/requirements-dev.txt
```
Set necessary env variables:
```shell
export APP_PROJECT_NAME='AI Software Engineering'
export AUDIO_RATE=16000
```
Check flake8:
```shell
flake8 app/
```
Run tests:
```shell
pytest
```
Check tests coverage:
```shell
pytest --cov app
```
