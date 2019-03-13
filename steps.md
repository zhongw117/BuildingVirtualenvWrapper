## $ python -m pip install --user virtualenvwrapper
## $ export WORKON_HOME=~/.virtualenvs
## $ source ~/.bashrc
## $ mkdir -p $WORKON_HOME

## $ echo $WORKON_HOME
## using "sudo find / -name virtualenvwrapper.sh" to load the exact path to 
## virtualenvwrapper.sh
### in my case, the path is /home/wilson/.local/bin/virtualenvwrapper.sh
### while my may find .local is not visible, so next 

## cd / to the root file
## ls and repeat cd **


## you will find virtualenvwrapper.sh 
## source /home/wilson/.local/bin/virtualenvwrapper.sh
## $echo "source /usr/local/bin/virtualenvwrapper.sh" >> ~/.bashrc
## done!
## create a new virtualenv:
## $ mkvirtualenv test_env2
