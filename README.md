# Creating the virtual environment
## install Poetry
```bash
pip install poetry
```
## create new a poetry project
Not needed if you manually create a project or want to run an existing project
```
poetry new <your_project_name>
```
## add a .venv directory to the project
poetry will write the dependencies in the .venv directory as a standard
Only for a new project. Not needed is you want to run an existing project
```bash
mkdir .venv
```
## add dependencies to the project
Not needed is you want to run an existing project
```
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
