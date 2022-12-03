# Automation Templates
Tempalates for the Automation platforms that I use.
Most of this is not yet ready for public consumption

## Prerequisites
I generally work inside of a Python virtual environment.  Depending on the automation platform, this may or may not be required.

Here is the configuration I currently use:
```commandline
pip install --upgrade pip
mkdir projects/ansible
apt install python3.8-venv
python3 -m venv venv --prompt="Ninja wk2"
pip install ansible pyvmomi
pip install --upgrade setuptools==62.0.0
pip install --upgrade git+https://github.com/vmware/vsphere-automation-sdk-python.git

```
