# textual-web-lab
This is a lab to experiment with Textual Web library.

### Features
- Textual Web can serve multiple Textual apps and terminals (as many as you like).


# Getting Started

1.	Project creation

Create a pyproject.toml with uv
```bash
uv init 
```

2.	Virtual Envinroment
Create a virtual environment
```bash
uv venv
```
Activate the virtual environment
```bash
.venv\Scripts\activate
```

3.	Install dependencies

Install a package in the virtual environment and add it to the pyproject.toml
```bash
uv add <package name>
```
# Usage
To run the application, use the following commmand:
```bash
textual-web --config pyproject.toml
```

 You will see the app is serving https://textual-web.io/2shsc9cdsj1w/calculator

 ![Sample](https://github.com/pilarcode/textual-web-lab/blob/main/docs/demo.png)
