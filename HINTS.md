### Create a new virtual environment
venv (for Python 3) allows you to manage separate package installations for different projects. It creates a “virtual” isolated Python installation. When you switch projects, you can create a new virtual environment which is isolated from other virtual environments. You benefit from the virtual environment since packages can be installed confidently and will not interfere with another project’s environment.


To create a virtual environment, go to your project’s directory and run the following command. This will create a new virtual environment in a local folder named .venv:
### python3 -m venv .venv

The second argument is the location to create the virtual environment. Generally, you can just create this in your project and call it .venv.

### venv will create a virtual Python installation in the .venv folder.


### Activate a virtual environment
Before you can start installing or using packages in your virtual environment you’ll need to activate it. Activating a virtual environment will put the virtual environment-specific python and pip executables into your shell’s PATH.
### source .venv/bin/activate

### To confirm the virtual environment is activated, check the location of your Python interpreter:
### which python

While the virtual environment is active, the above command will output a filepath that includes the .venv directory, by ending with the following:
### .venv/bin/python

### MORE https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/

### pip install -r requirements.txt
