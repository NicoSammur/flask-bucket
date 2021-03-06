### Setup
``$ sudo apt-get install python3-venv
$ python3 -m venv venv
$ source venv/bin/activate
$pip install -r requirements.txt``

### Setup database
``$ python3
>> from app import db
>> db.create_all()
>> exit()``

### run
``$ python3 app.py``
