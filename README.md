# PyCodeGraph: Python Code Dependency Explorer
https://yanz-24.github.io/PyCodeGraph/
## About

PyCodeGraph is a free, interactive tool for visualizing the structure of Python code. Upload a Python script or paste your code to explore its functions, imports, and package dependencies through an interactive network. The tool was vibe coded as a lightweight, accessible way to understand how different parts of a Python script relate to one another, without installing additional software.

## Understanding the Node Types

The network organizes code elements into three categories:

- **Local Functions (Blue):** Functions defined within your Python code.
- **Imported Symbols (Orange):** Functions, classes, and other symbols imported from external modules.
- **Packages (Green):** Modules and packages that provide the imported symbols.

## Privacy and Limitations
All analysis runs locally in your browser. Your code is not uploaded to a server. 

This offline analyzer uses a lightweight JavaScript source scanner, not Python's full AST.
