all: html

html:
	ipython nbconvert --to slides git_tutorial_slides.ipynb

serve: html
	python -m SimpleHTTPServer 8000
