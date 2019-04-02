# Python Flask + MongoDB sample for testing

## Instructions

**Step1**: Install python3

**Step2**: Setup MongoDB

- Install mongodb

- Create db "sample" and collection "todo"

```
> db.create.sample
sample.create.sample
> use sample;
switched to db sample
> db.createCollection("todo")
{ "ok" : 1 }

```
**Step3**: Clone sample code

`git clone https://github.com/keepwalking86/python-mongodb-sample.git`

**Step4**: Creation of virtual environments

```
cd python-mongodb-sample
python3 -m venv .
```

**Step5**: Install Flask, bson & pymongo

>pip install -r requirement.txt

**Step6**: Run Flash app

>python app.py

**Step7**: Access web server by browser

>http://localhost:5000


