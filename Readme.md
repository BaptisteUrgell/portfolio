# My portfolio

<div align="center">
    <img src="app/assets/img/logo/fastapi.png" alt="fastapi-logo" width="300"/><img src="app/assets/img/logo/bootstrap.png" alt="Bootstrap-logo" width="300"/>
</div>


## Overview

This is my personal web site, you can reash it at [http://urgell.freeboxos.fr:32769/](http://urgell.freeboxos.fr:32769/).
This project use [FastAPI](https://fastapi.tiangolo.com/) framework to create the API and [Bootstrap](https://getbootstrap.com/) for the design. 

## Installation

To install all the requirements, use the package manager [pip](https://pip.pypa.io/en/stable/) and type this in your terminal.

```bash
pip install -r /path/to/requirements.txt
```

## Usage

First of all, you have to launch the app :
```bash
uvicorn main:app --reload
```

This command should create the local server on your computer with the app running on it.

Then, go to [http://localhost:8000/](http://localhost:8000/) and enjoy it !

## Documentations

- For app information go to [http://localhost:8000/info](http://localhost:8000/info).

- To visualize and test all the endpoints and the API routes available, go to [http://localhost:8000/docs](http://localhost:8000/docs) and you should see the swagger page.

- To see a more detailled documentation go to [http://localhost:8000/redoc](http://localhost:8000/redoc).