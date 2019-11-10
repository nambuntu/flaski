Flasky
======
### To build project on Linux / Mac
```bash
python3 -m venv venv
. venv/bin/activate
pip install -r requirements/dev.txt
export FLASK_APP=flasky.py
flask deploy
```
![PyCharm setup on Mac](setup/mac.png)
### To build project on Windows
```shell script
python -m venv venv 
.\venv\Scripts\activate.bat
pip install -r requirements\dev.txt
set FLASK_APP=flasky.py
flask deploy
```
#### Setup a VENV for PyCharm
![Select venv on Windows](setup/venv.jpg)
#### Create a run configuration 
![PyCharm setup on Windows](setup/windows.jpg)