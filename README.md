# python-versions
Simple .sh files for installing and managing different Python versions on Linux.

# Usage
1. Add execution permission to the file you wanna use. For example: `chmod +x python3.8_install.sh`\
2. Run the desired file. For example: `./python3.8_install.sh`

# Venv
Create Python 3.8 virtual environment in subdirectory of `venv3.8`\
`python3.8 -m venv .venv3.8`\
Switch to the virtual environment\
`source .venv3.8/bin/activate`\
Perform commands as usual\
`python3.8 -m pip install -r requirements.txt`\
