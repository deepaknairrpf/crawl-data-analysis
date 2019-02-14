# crawl-data-analysis

## Instructions to run:
All relevant code can be found in Assignment.ipynb notebook file.
Notebook files can be run inside a docker container as follows :

1. cd into the cloned repo.
2. Run the command `docker run -v `pwd`:/opt/app/data -p 8888:8888 mikebirdgeneau/jupyterlab`. This mounts the present directory to be accessible inside jupyterlab and starts a session in port 8888.
3. Navigate to the given URL in a browser and run the Assignment notebook.

