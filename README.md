# uv commands:
In this project we are using uv to manage the dependencies instead of using pip and the deatils of the commands and the files are mentioned below. One benefit is that as you add more dependencies, uv will automatically update the pyproject.toml file and the uv.lock file.

1- "uv init"  (This will create a new project and install the dependencies)
2- "uv add langgraph python-dotenv" (This will create a new virtual environment and install the dependencies)
3- To select the virtual environment .venv use "source .venv/bin/activate"


pyproject.toml: this contains the dependencies for the project.

uv.lock: this contains the exact dependencies for the project, but you don't need to worry about it.
