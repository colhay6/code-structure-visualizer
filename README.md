# Code Structure Visualizer

The Code Structure Visualizer is a local web-based tool designed to help developers visualize and analyze the structural relationships within their codebase. This tool leverages D3.js to provide an interactive graphical representation of file dependencies, allowing you to better understand how various components in your projects are interconnected.

## Why?

When working on client projects and needing to quickly understand and contribute to new codebases, I found the file explorer in Visual Studio Code to be lacking. This tool provides a visual context of file dependencies, serving as an alternative to VSCode's file explorer. By using this tool, I can quickly orient myself within a new codebase and develop a stronger mental map of the structure and interactions of files.

## Main Features

- **File Explorer Navigation**: Navigate through your directory using the integrated file explorer, selecting single or multiple files to highlight their relationships.
- **Interactive Graph**: Click on a node within the graph to open the corresponding file in Visual Studio Code, assuming your machine setup is correctly configured.

## Supported File Types

The tool currently supports the following file types:
- Python
- JavaScript
- HTML/CSS
- Java

## Usage

To use the tool, follow these steps:

1. Open the `code-structure-visualizer.html` file in Chrome.
2. Select a directory that you want to visualize.
3. Provide a base path to that directory.

Following these steps will generate a visual representation of the structural relationships within your specified directory.

## To Do

- Add support for more programming languages.
- Implement the ability to refresh the directory to quickly import changes.
- Enhance functionality for viewing and navigating within projects.
