# Streamlit Starter

- Fork down this repo to get started with a streamlit template


# How to replicate
  1. Fork project and pull down your repo
  2. Make sure streamlit and other packages are installed
     - I recommend using Poetry for package management
  3. Build out your streamlit app
  4. freeze you packages into a requirements.txt file and push
  5. Upload your repo to streamlit to run app in the cloud


# Python Environment Setup
Activate your virtual environment and make sure you have installed Streamlit

If using conda you can run:
  - `conda install streamlit`

Any others can use:
  - `pip install streamlit`

# Running the App Locally
Run `streamlit run app.py` from the command line.

If you receive a `streamlit.cli` error try running:
  -   `python -m streamlit run app.py`


# Run using Poetry
This repo also utilizes poetry for package management. 
  - `conda create -n [environment_name] python=3.11`
  - `poetry install` \n
#### Once you have an environment like above, you can reuse it with any other projects that use poetry and python 3.11
