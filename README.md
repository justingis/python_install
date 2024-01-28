# python_install
Various code for getting Python up and running

macos Python install locations:
  - /Library/Frameworks/Python.framework/Versions/3.11/bin/python3

Verify your Python installation by opening your zprofile: nano ~/.zprofile

Set Terminal Alias:
 - nano ~/.zshrc
   - alias python=python3
   - alias pip=pip3

pip3 install --upgrade pip

Create Python Virtual Environment

Switch to project directory: (ex. cd /Users/justinhawley/repos/tutorial)
python -m venv venv --system-site-packages
Activate virtual environment: source venv/bin/activate
Verify environment has GDAL package: pip list (can upgrade pip here as well: pip install --upgrade pip)
