
# mlapp

https://imelike-ml-app.herokuapp.com

# Demo

Launch the web app:

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://imelike-ml-app.herokuapp.com)

# Reproducing this web app
To recreate this web app on your own computer, do the following.

### Create conda environment
Firstly, we will create a conda environment called *ml*
```
conda create -n ml python=3.11.1
```
Secondly, we will login to the *ml* environement
```
conda activate ml
```
### Install prerequisite libraries

Pip install libraries
```
pip install -r requirements.txt
```
###  Launch the app

```
streamlit run app.py
```
