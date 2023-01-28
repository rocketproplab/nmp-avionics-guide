# Contributing to this Guide

This guide lives on a public GitHub repository, allowing anyone to submit suggested changes via a Pull Request. If you think this guide can be expanded or improved in any way, feel free to contribute!

## MkDocs
This site is powered by Material MkDocs. MkDocs builds markdown files into static websites. Material MkDocs is a theme that adds additional formatting and features.

For full documentation visit [mkdocs.org](https://www.mkdocs.org) or [Material MkDocs](https://squidfunk.github.io/mkdocs-material/).

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