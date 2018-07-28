# Train Data Parser

## Setup:

Install Nodejs:

Link: https://nodejs.org/en/download/package-manager/

### Ubuntu

Link: https://nodejs.org/en/download/package-manager/#debian-and-ubuntu-based-linux-distributions

1. `curl -sL https://deb.nodesource.com/setup_8.x | sudo -E bash -`
2. `sudo apt-get install -y nodejs`

### Windows

Link: https://nodejs.org/en/download/

Simply download the installer.

### How to run?

`python train_data_parser.py`

### Instructions

train_data_parser.py file has a function called `get_json` which takes three parameters:
1. raw response text received from the server.
2. file_path where javascript file will be saved.
3. json_path where correctly parsed json will be saved.

It outputs the correctly parsed json.
