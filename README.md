# TDM tutorial using CORE resources

## Requirements

Register a CORE API key and place it to a file called api_key.secret that is git ignored to avoid exposing it publicly

To run python notebooks you would need a notebook server. The best way to install one locally is the anaconda distribution you can download and install (versions for windows, mac, linux):
https://www.continuum.io/downloads

After you install anaconda, run in the command line:

git clone https://github.com/oacore/collaboration_discovery_experiment.git

cd collaboration_discovery_experiment

jupyter notebook


A server will start on http://localhost:8888 showing all the available notebooks of the current folder.

Highly recommended:

Run create_cache python notebook to populate /data folder with cached data to be used for the main notebook (tdm demo). Only data files of repository 1 are included in this git repo (to avoid tracking of big (~10Mb) files)



## Run

jupyter notebook
select tdm demo.ipynb
