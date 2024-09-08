# Repository-Structure-Graph

This project is designed to create a directed graph representing the structure of an entire repository. By utilizing **Tree-Sitter**, it parses code to visualize the relationships between methods and function calls across multiple languages. This graph can then be used to provide context for Large Language Models (LLMs) when interacting with codebases, enhancing understanding and improving LLM-assisted development tasks such as code generation, refactoring, and documentation.

## Features

- **Multi-Language Support**: Supports parsing and graph generation for multiple programming languages using Tree-Sitter's wide language support.
- **Graph Visualization**: Generates directed graphs of methods and their call relationships, giving a clear, high-level view of the structure of a codebase.
- **LLM Integration**: Provides whole-repository context to improve interactions with LLMs, making it useful for various tasks like code navigation, analysis, and automated code changes.
- **Customizable**: Easily adaptable to support additional languages or specific repository structures.

## Technologies Used

- **Tree-Sitter**: A powerful parser used for syntax tree generation across multiple programming languages.
- **NetworkX**: For generating and analyzing the structure of the repository as a graph.
- **Matplotlib**: For visualizing the graph of the repository structure.
- **Python**: The main language used for this project, integrating the different tools and libraries.

## Setup

Follow the steps below to install the necessary dependencies and get started.

### Prerequisites

Ensure you have Python 3.8+ installed on your machine.

### Install Python Dependencies

First, install the necessary Python dependencies:

```bash
pip install tree-sitter==0.21.3 tree-sitter-languages networkx matplotlib
