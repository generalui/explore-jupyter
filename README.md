# Welcome

This project has been created to explore working with [Jupyter](https://jupyter.org/index.html) notebooks and related offerings.

## Getting started

The easiest way to use this repo is to have [Docker](https://www.docker.com) installed and configured on your development machine.

Once this is complete, you can spin up the project by running:

```sh
$ npm start

> npm run docker:down && npm run docker:start


> explore-jupyter@0.0.0 docker:down /Users/rob/repos/genui/explore-jupyter
> docker-compose down

Removing network explore-jupyter_default
WARNING: Network explore-jupyter_default not found.

> explore-jupyter@0.0.0 docker:start /Users/rob/repos/genui/explore-jupyter
> docker-compose up

Creating network "explore-jupyter_default" with the default driver
Pulling datascience-notebook (jupyter/datascience-notebook:)...
latest: Pulling from jupyter/datascience-notebook
5b7339215d1d: Pull complete
14ca88e9f672: Pull complete
              . . . . . . . . . . . . . . . .
datascience-notebook    | Executing the command: jupyter notebook
datascience-notebook    | [I 15:56:01.330 NotebookApp] JupyterLab extension loaded from /opt/conda/lib/python3.7/site-packages/jupyterlab
datascience-notebook    | [I 15:56:01.330 NotebookApp] JupyterLab application directory is /opt/conda/share/jupyter/lab
datascience-notebook    | [I 15:56:01.333 NotebookApp] Serving notebooks from local directory: /home/jovyan
datascience-notebook    | [I 15:56:01.333 NotebookApp] The Jupyter Notebook is running at:
datascience-notebook    | [I 15:56:01.333 NotebookApp] http://db56fc80aefd:8888/?token=94117cd90212b32e70767d7b1d1dbf594521ed6f03ce8989
datascience-notebook    | [I 15:56:01.333 NotebookApp]  or http://127.0.0.1:8888/?token=94117cd90212b32e70767d7b1d1dbf594521ed6f03ce8989
datascience-notebook    | [I 15:56:01.334 NotebookApp] Use Control-C to stop this server and shut down all kernels (twice to skip confirmation).
datascience-notebook    | [C 15:56:01.394 NotebookApp]
datascience-notebook    |
datascience-notebook    |     To access the notebook, open this file in a browser:
datascience-notebook    |         file:///home/jovyan/.local/share/jupyter/runtime/nbserver-6-open.html
datascience-notebook    |     Or copy and paste one of these URLs:
datascience-notebook    |         http://db56fc80aefd:8888/?token=94117cd90212b32e70767d7b1d1dbf594521ed6f03ce8989
datascience-notebook    |      or http://127.0.0.1:8888/?token=94117cd90212b32e70767d7b1d1dbf594521ed6f03ce8989
```

To work with Jupyter, click on the URL - [http://127.0.0.1:8888/?token=94117cd90212b32e70767d7b1d1dbf594521ed6f03ce8989](http://127.0.0.1:8888/?token=94117cd90212b32e70767d7b1d1dbf594521ed6f03ce8989) in this example.

Once you have finished with your work - or if you would like to stop the project from running:

```sh
// Be sure to press CTRL+C to stop the running container
$ npm run docker:down
```

## Resources

[Jupyter Data Science Stack + Docker in under 15 minutes](https://towardsdatascience.com/jupyter-data-science-stack-docker-in-under-15-minutes-19d8f822bd45)
