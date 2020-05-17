# Ansible playbook for automating a setup of a new Windows Subsystem Linux (Ubuntu) for a rich development experience

This will setup a new laptop for software development. 

## Requirements:

1. Ubuntu 18.04 is installed.
2. Ansible is installed.  Can do so by running:

```
sudo apt-get -y install python3-pip python3-dev libffi-dev libssl-dev
pip3 install ansible==2.8.4 --user
```

### How to use:

##### Running the ansible playbook:

```
 $ git clone https://github.com/genomics-geek/setup-wsl-ubuntu-playbook.git
 $ cd setup-wsl-ubuntu-playbook
 $ ansible-playbook setup.yml -i hosts -l local
```

### What this includes:

#### Languages

+ Python3
+ GO
+ Nim
+ Java

#### Databases

+ Postgres
+ MySQL

#### Caches

+ Redis
+ Memcached

#### Virtual Environment managers

+ pyenv
+ plenv
+ jenv

#### Javascript tooling

+ Node
+ Yarn
+ Create React App

#### Code formatters

+ Autopep8
+ Prettier

