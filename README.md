# RPL NMP Avionics Guide Site
A [Material MkDocs](https://squidfunk.github.io/mkdocs-material/) site that provides guidance for Rocket Propulsion Lab's New Member Project regarding the development of a flight computer for a model rocket.


## Building the Site Locally
### Prerequisites

Before building, install the following software:

- Python 3.10
- Pip, the Python Package Manager

### Building the Site

While contributions can be made by directly adding and editing markdown files, it is generally nicer to continuously build the site to see how changes look to normal readers.

1. Open a terminal window and navigate to the root directory of this project.
2. Type `pip install -r requirements.txt` to install required dependencies.
3. Type `mkdocs serve` to start a local development server.

When ready to build the site as a static HTML website, type `mkdocs build`.