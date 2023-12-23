# Creating the virtual environment
## install Poetry
```bash
pip install poetry
```
## create a poetry project
Not needed if you manually create a project or get it from a repository
```bash
poetry new <your_project_name>
```
## add a .venv directory to the project
poetry will write the dependencies in the .venv directory as a standard
```bash
mkdir .venv
```
## add dependencies to the project
```bash
poetry add <package-name>
```
## installing dependencies
```bash
poetry install --no-root
```

# Activating the virtual environment
```bash
.venv\Scripts\activate
```
