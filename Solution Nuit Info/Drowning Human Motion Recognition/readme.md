# create virtual env
virtualenv venv

# activate venv
source ./venv/Scripts/Activate

# install requirements
pip install -r requirements.txt

# run motion recognition
python motion_recognition.py

