# Covid19 basic data analysis

Try to make sense to raw data with some basic analysis on Covid-19 pandemic in Italy. 
Raw and machine-readable data have been provided on a daily basis by institutional departments.


Here's the [https://github.com/pcm-dpc/COVID-19](repo).

## What you need

### With Virtual Environments

- Create a Python3.x Virtual Environment:

	```
	python3.x -m venv venv
	```

- Activate it (run this command each time you want to work with the notebook):
	
	```
	source  venv/bin/activate
	```

- Install dependencies

	```
	pip install -r requirements.txt
	```

- Run Jupyter notebook locally
	
	```
	jupyter-notebook
	```

- Get the link (along with the token), copy and paste into a browser address bar;

- Enjoy!

### With Docker

If you're comfortable with Docker:
	
	
	docker run -ti --rm -p 8889:8888 -v `pwd`:/home/jovyan/work jupyter/base-notebook

Then install dependecies with the ```pip``` command.


## See the running notebook on binder

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/brunifrancesco/covid19/HEAD?filepath=Covid%20analysis.ipynb)
