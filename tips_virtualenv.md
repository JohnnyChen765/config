### Python virtualenv

In a terminal, run

	pip3 install virtualenvwrapper

Add to your `~/.bashrc` or `~/.bash_profile`

	export WORKON_HOME=$HOME/.virtualenvs
	export PROJECT_HOME=$HOME/dev
	export VIRTUALENVWRAPPER_PYTHON=/usr/local/bin/python3
	export PIP_VIRTUALENV_BASE=/usr/local/bin/python3
	source /usr/local/bin/virtualenvwrapper.sh

Then, in your terminal, take the changes into account by running (`~/.bash_profile` on MacOS)

	source ~/.bashrc

### Create virtualenv

Then create a python3 virtualenv

	mkvirtualenv project_name -p python3

And then access the virtualenv with 
```
workon project_name
```
