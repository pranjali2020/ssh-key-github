# ssh-key-github
How to create the ssh key in github, which is used to clone repository in local.

youtube refrence link : youtube.com/watch?v=4E7-2cIcF2U

Problem:
I was trying to clone the git repo in my a_pmittal account, but i was getting permission denied issue.

Resolved Using:
1. I created ssh key in my github account (pmittal-cswg).
2. I used ssh key command to clone:
   git clone git@github.com:pmittal-cswg/atom-anomaly-detection.git


## Python project requirements:


## How to Install 

1. Clone the repository 

```
git clone https://github.com/pmittal-cswg/atom-anomaly-detection.git
or {create ssh key and use the below command to clone the repo}
git clone git@github.com:pmittal-cswg/atom-anomaly-detection.git
```

2. Create a virtual environment and activate

```
python -m venv .venv
.venv\Scripts\activate.bat
```

3. Install dependencies 

```
pip install -r requirements.txt
```

4. Manually copy the settings.py file

## How to run the application

1. Activate the virtual environment
```
cd to\the\paretnt\installation\folder
.venv\Scripts\activate.bat
```
3. Run the application 

```
python index.py
```
