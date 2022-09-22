# {{cookiecutter.project_name}}

## Requirements

- `python`: >= 3.6
- `docker`: >= 19

## Setup

> Run this commands inside project folder only

### Starting docker

- We'll need docker then run: `docker-compose up -d`.*This is for newbies only*.
- **_Voilá_**. Now visit your [**Odoo site**]('https://127.0.0.1:{{cookiecutter.odoo_port}}').

### Development mode

- Create a virtual enviroment: `python -m venv .venv`
- Set the proper source: `source .venv/bin/activate` *Use the proper activate script for ou OS.*
- Install odoo package: `pip install -r requirements.txt`

**Now we are ready to rush into development mode.**

The folder `addons` is ready to hold any future **Odoo module or addon** implementation.
