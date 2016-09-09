## Project: Tournament Results
## Sara Vagnarelli

## Description:
This project consists in a database schema to model a Swiss tournament system in which players are not eliminated and paired with another player with the closest score.

### Requirements:
Virtual Box, Vagrant, Python

### How to install:

* [Clone the fullstack-nanodegree-vm](https://github.com/udacity/fullstack-nanodegree-vm) in the vagrant directory of the clone
* Delete the existing tournament directory and clone this [repo](https://github.com/saravgn/stournament.git)
* In the command line navigate to the vagrant directory and launch the VM

```bash
vagrant$ vagrant up
vagrant$ vagrant ssh
```
* Navigate in the VM to the project directory inside the vagrant directory

```bash
cd /vagrant/stournament
```

* Create the database schema
```bash
psql - f tournament.sql
```

* Then you can execute the tests module
```bash
python tournament_test.py
```

### Citations

Udacity and StackOverflow forums.