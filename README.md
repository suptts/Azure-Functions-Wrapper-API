[![Python application test with Github Actions](https://github.com/suptts/tts-python-fundamental/actions/workflows/testing_ci.yml/badge.svg)](https://github.com/suptts/tts-python-fundamental/actions/workflows/testing_ci.yml)

# tts-python-fundamental
This is learning python project for tts devops2023

* ให้ clone project มาที่เครื่องเรา `git clone https://github.com/suptts/tts-python-fundamental.git`
* เข้าไปใน project folder `cd tts-python-fundamental`
* ให้ Create a Python Virtual Environment ด้วยคำสั่ง `python3 -m venv ~/.venv` หรือ `virtualenv ~/.venv` 
* จากนั้นรันคำสั่ง `source ~/.venv/bin/activate` หรือ `source venv.sh`
* แล้วค่อยรัน run `make all`


ตัวอย่าง venv.sh แบบง่าย

```
#!/usr/bin/env bash

python3 -m venv ~/.venv
echo "source ~/.venv/bin/activate" >> .bashrc

source ~/.venv/bin/activate
```


