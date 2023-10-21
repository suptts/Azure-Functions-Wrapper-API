[![Python application test with Github Actions](https://github.com/suptts/tts-python-fundamental/actions/workflows/testing_ci.yml/badge.svg)](https://github.com/suptts/tts-python-fundamental/actions/workflows/testing_ci.yml)

## Table of contents

- [Quick start](#quick-start)
- [Status](#status)
- [Thanks](#thanks)
- [Sup](#sup)

# tts-python-fundamental
This is learning python project for tts devops2023

* ให้ clone project มาที่เครื่องเรา `git clone https://github.com/suptts/tts-python-fundamental.git`
* เข้าไปใน project folder `cd tts-python-fundamental`
* ให้ Create a Python Virtual Environment ด้วยคำสั่ง `python3 -m venv ~/.venv` หรือ `virtualenv ~/.venv` 
* จากนั้นรันคำสั่ง `source ~/.venv/bin/activate` หรือ `source venv.sh`
* แล้วค่อยรัน run `make all`


ตัวอย่าง venv.sh แบบง่าย

```bash
#!/usr/bin/env bash

python3 -m venv ~/.venv
echo "source ~/.venv/bin/activate" >> .bashrc

source ~/.venv/bin/activate
```

## Step 1: Install the Required Python Version
```
brew install python@3.8
Python has been installed as
  /opt/homebrew/bin/python3.8 
brew install python@3.9
Python has been installed as
  /opt/homebrew/bin/python3.9
brew install python@3.10
brew install python@3.11
```

## Step 2: Create a Virtual Environment
```
virtualenv -p /opt/homebrew/bin/python3.8  myenv3.8
source myenv3.8/bin/activate
python -V
deactivate

virtualenv -p /opt/homebrew/bin/python3.9  myenv3.9
source myenv3.9/bin/activate
python -V
deactivate

virtualenv -p /opt/homebrew/bin/python3.10  myenv3.10
source myenv3.10/bin/activate
python –V
deactivate
```

## โครงสร้าง files และ folder structure ของ Project ที่เราจะ develop  

ตัวอย่าง 

```text
tests/
└── folder2/
    ├── folder3/
    │   ├── file1
    │   └── file2
    └── folder4/
        ├── file3
        └── file4
```

## Build Solutions and AI Apps with OpenAI (GPT-3, Codex, DALL-E)

เราจะนำเอา ChatGPT มาใช้เพื่อทำ Business Solutions เป็นการเรียนรู้และนำ Technology มาใช้งานจริง

## Roadmap

เราจะเรียนรู้เกี่ยวกับ

- OpenAI และ ChatGPT
- การ setup development environment
- การ create serverless wrapper API with ChatGPT
- การ Integrate ChatGPT เข้ากับ platform ต่างๆเพื่อทำเป็น Business Solutions



Enjoy :metal:

ให้ดูเนื้อหาใน docs โฟล์เดอร์. [^1]

[^1]: This is the footnote.
