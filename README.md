# AsrIran web crawler project

this project will crawl asriran website and extract information from 150000 news and write them to a csv file.

# Installation

this project is written with python language and scrapy crawling framework so you need to install python in your computer,
you can access python official website for downloading python via [this link](https://www.python.org/).

after installing python, clone the project into your computer and open a terminal in project root directory, now you need to create
and activate a python virtual environment, to do that follow the instruction bellow:

1- creating the virtual environment
windows:

```bash
py -m venv venv
```
mac or linux:

```bash
python3 -m venv venv
```

2- activating the virtual environment
windows:

```bash
.\venv\scripts\activate
```

mac or linux:

```bash
source venv/bin/activate
```
now you have an active virtual environment it is time to install project requirements, for that enter the command bellow:
windows:

```bash
pip install -r requirements.txt
```

mac or linux:

```bash
python3 -m pip install -r requirements.txt
```
now please wait for project dependencies to download this may take a few minutes, after that you can command the crawler to start crawling by simply typing
this command in the terminal:

```bash
scrapy crawl AsrIran
```


