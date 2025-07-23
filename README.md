# "Spatial: Networks, Interaction, & Econometrics for Migration"

NERSA/NARSC Program in Mobility, Migration & Regional Science

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/knaaptime/workshop-nersa25)

## Install and Run

To run locally:

- install [pixi](https://pixi.sh/dev/installation/)
- clone this repository, follow below

To run in codespaces:

- click the 'open in codespaces' button above
  - the default config will include at least 8 cores (dont go below 32gb memory), but you can crank it up for better performance

- `pixi install`
- `pixi run jupyter lab`

if running in a codespace this starts a jupyter server on the VM's 'localhost'.
Open an existing notebook (or start a new one). When selecting a kernel, choose
'Existing jupyter server' and copy/paste the URL with token from the terminal

edit the notebooks as you like

**if you want to use the jupyterlab interface instead of VSCode**:

- in the bottom panel click the "ports" tab
- click the "add port" button
  - type 8888
  - click the URL in the "forwarded address column
- click back in the vscode interface
  - click the "terminal" tab in the bottom panel
  - scroll up and copy the *token* string from the URL
  - click back into jupyterlab and paste the token


## Overview

- spatial data and analysis in python
- encoding spatial relationships
- model flows via spatial interaction
- model flows via spatial econometric interaction

## Introduction

open source and open science

- pixi & conda
- jupyter
- python
- pysal 
- geosnap

## spatial data in python

- pandas
- numpy
- shapely
- geopandas
- census and lodes

## spatial graphs

encoding relationships between spatial objects

- contiguity
- k-nearest neighbors
- distance
- flows

## spatial interaction models

modeling the flow between $o$ and $d$ as a function of push and pull factors

- gravity model (unconstrained) 
- attraction constrained
- production constrained
- doubly constrained

## spatial econometric models

multiple graphs: modeling spatial dependence in the flow between $o$ and $d$ via $^oW$, $^dW$, and $^{od}W$

- spatial dependence
- OD-Graphs
- lag models
- error models