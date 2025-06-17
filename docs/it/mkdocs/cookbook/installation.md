---
status: new
# date: 2024-06-01
created: 2025-06-17
# updated: 2024-06-10

title: Installation
description: My personal Material for MkDocs cookbook.
authors:
  - Axel Bjelke

#hide:
#  - toc
#  - navigation
# icon: 
tags:
  - mkdocs
---

# Installation

Start with VS Code in the base directory of the project defined in prerequisites, and use the integrated terminal. ==UPDATE== MORE!

## Install Material for MkDocs

Installation method: In this guide we use the [Python package](https://pypi.org/project/mkdocs-material/) which is the recommended one.

??? info "Python virtual environment"
    It's recommended to run Python in a virtual environment.

    ===  "Linux / Windows"
        ``` bash title="Create a Python virtual environment"
        python -m venv venv
        ```

    This creates the folder `\venv` in your project folder (the folder name is not important here).
   
    ===  "Linux"
        ``` bash title="Activate the Python virtual environment"
        source venv/bin/activate
        ```
    
    ===  "Windows"
        ``` ps title="Activate the Python virtual environment"
        .\venv\Scripts\activate
        ```
    You should see `(venv)` at the start of your prompt, indicating the environment is active.

With the Python virtual environment activated, install MkDocs Material using [pip](https://realpython.com/what-is-pip/).

``` bash
pip install mkdocs-material
```

Verify the installation:
``` bash
mkdocs --version
```
