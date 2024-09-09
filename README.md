# RAG System with LlamaIndex and Poetry

## Overview
This repository contains a project for implementing a Retrieval-Augmented Generation (RAG) system using the LlamaIndex library. Poetry is used to manage the virtual environment and dependencies for this project.

## Features
- **LlamaIndex**: Integrate LlamaIndex for enhanced retrieval capabilities.
- **Poetry**: Manage project dependencies and virtual environment with Poetry.
- **Jupyter Notebooks**: Execute and interact with RAG components through Jupyter Notebooks using Gradio.

## Requirements
- Python 3.8 or higher
- Poetry
- Jupyter Notebook

## Installation
Follow these steps to set up the project:

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/your-repository.git
    cd your-repository
    ```

2. Install Poetry (if you haven't already):

    For installation instructions, visit the [Poetry website](https://python-poetry.org/).

3. Install project dependencies:

    ```bash
    poetry install
    ```

4. Activate the virtual environment:

    ```bash
    poetry shell
    ```

5. Install Jupyter Notebook within the virtual environment:

    ```bash
    poetry add notebook
    ```

## Usage
1. Setup your LlamaIndex:

    Configure LlamaIndex according to the [LlamaIndex documentation](https://www.llamaindex.ai/).

2. Run the Jupyter Notebook:

    Navigate to the `scripts` directory and start Jupyter Notebook:

    ```bash
    cd scripts
    jupyter notebook
    ```

    This will open Jupyter Notebook in your default web browser.

3. Open the `.ipynb` files:

    In the Jupyter Notebook interface, open the `.ipynb` files located in the `scripts` directory. These notebooks contain code to execute and interact with the RAG system. Each notebook includes cells to run, which will also display Gradio interfaces if applicable.

4. Execute the cells:

    Run all the cells in the notebook to initialize and interact with the RAG system. Ensure you follow any instructions provided within the notebooks for proper execution and configuration.

## Project Structure
- `scripts/`: Contains Jupyter Notebooks for running and testing the RAG system.
- `README.md`: This file.
- `pyproject.toml`: Poetry configuration file.

## Contributing
If you'd like to contribute to this project, please fork the repository and submit a pull request with your changes. Make sure to follow the coding standards and include tests where applicable.

## License
This project is licensed under the MIT License.

## Contact
For any questions or issues, please open an issue on GitHub or contact [joselorenzogarcia1501@gmail.com](mailto:joselorenzogarcia1501@gmail.com).
