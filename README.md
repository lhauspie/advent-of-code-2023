# Advent of Code 2023

This year, I decided to practice Python.

## How to run

Just execute:
```shell
docker run -it --name jupyter-notebook -p 10000:8888 -v "${PWD}":/home/jovyan/work quay.io/jupyter/minimal-notebook:2023-10-20
```

Then go to http://localhost:10000/token=<token> (with <token> the token displayed in the console)
