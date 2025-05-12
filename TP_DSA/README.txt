You can start by activating the virtual environment and installing the required dependencies.

`source venv/bin/activate`

`pip install -r requirements.txt`

You then need to activate the virtual environment you created in Jupyter, with command:
`python -m ipykernel install --user --name=venv`

Then start the jupyter server:
`jupyter lab`

And open the notebook. In the menu, choose "kernel" -> "Change kernel" to choose the venv kernel you just added. You can now get started!