## Create virtual Env for project ##
python -m venv ./venv

## Activate the virtual environment  ##
.\venv\Scripts\activate

## Deactive ENV ##
deactivate

## Install Flask ##
pip install flask


## Init rasa with expose api ##
rasa run --enable-api --debug --cors "*"

## Run flask api ##
python .\main.py

## Use jquery in html for contact with Rasa use ##
index_old.html

## Use http request for contact with Rasa use ##
index.html