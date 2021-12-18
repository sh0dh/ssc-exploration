# ssc-exploration
Exploring SSC (Shadowy Super Coder) NFT from GensysGo

# How to setup this repository

- Need to install 
  - `python v3.9.6` and above
  - `poetry v1.1.11`
  - Both these were originally installed on my system using `asdf`, would advise everyone to try out `asdf` for a good multi-environment setup
- Run: `poetry install` and all the libraries will in install in `.venv` folder

# Running jupyter notebooks
- `poetry` sets up a venv automatically (no need to activate anything, once you cd in project's root folder it is activated)
- Use: `poetry run jupyter notebook` to start the jupyter server (`poetry run <any-file-or-command>` is proxy for `python <any-file-or-command>`)
