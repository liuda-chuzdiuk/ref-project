"# ref-project" 

## Installation

Python3 must be already installed

```shell
git clone https://github.com/liuda-chuzdiuk/ref-project.git
python3 -m venv venv
source venv/bin/activate (on macOS) & venv\Scripts\activate (on Windows)
pip install -r requirements.txt
python3 manage.py makemigrations
python3 manage.py migrate
python manage.py runserver # starts Django Server
```
