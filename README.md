# PK Funding System 

## Description

Do more with your cryptocurrency by getting the community involved. The goal of the PK Funding System is to enable community members to complete projects and be paid for the projects by other community members. 

The PK Funding System was written entirely in Python. It was originally developed by dsc_ (skftn) for the Wownero currency but later updated by various community members to be accepted for PK and other cryptonote currencies. 

## Features
- Simplistic user system
- Proposal system
- Accounting system
- Stats per proposal
-- Coins received
-- Coins paid out
-- Coins available
- Comment system per proposal
- More in development

## Installation (locally)

Better instructions to follow in the future.

### Install dependancies

```sudo apt install python-virtualenv python3 redis-server postgresql-server-dev-* postgresql postgresql-client python-pip virtualenv git```

Create a Postgres user/database for this project

```
git clone https://github.com/camthegeek/pk-funding-system.git
cd pk-funding-system
virtualenv -p /usr/bin/python3 <venv>
source <venv>/bin/activate
pip install -r requirements.txt
cp settings.py_example settings.py
- change settings accordingly
python run_dev.py
```

### to-do

- [] rate limit posting of proposals per user
- [x] Define coin variable
- [] Define one exchange API URL
- [] Automated setup
- [] User follow proposals
