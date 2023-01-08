# Resemble

Resemble is a basic sm64ex-coop server written in python, with a goal of being as user-friendly as possible.

## Requirements:
- Python 3.11
- python-box

## Setup:
### Windows:

- Installing Python:
  1. Install the latest Python from [this link](https://www.python.org/downloads/)
  2. Open Powershell as an administrator and run `python3.11 -m ensurepip`

- Installing libraries:
  1. Install python-box with `python3.11 -m pip install python-box`
  
### Linux:
  
- Installing Python:
  1. Open a terminal, and run `sudo apt-get update`
  2. Add the ppa repository with `sudo apt-add-repository ppa:deadsnakes/ppa`
  3. Install python with `sudo apt-get install python3.11`
  4. Run `curl -sS https://bootstrap.pypa.io/get-pip.py | python3.11` to install pip

- Installing libraries:
  1. Install python-box with `python3.11 -m pip install python-box`

## How to run:
Execute main.py and provide an IP to host the server on, you may also provide a custom port.

If your server uses a domain to connect, host on the IP of the corresponding subdomain.

You can run `python main.py help` for more info.

## Notes and credits:
- Based off of djoslin0's [sm64ex-coop](https://github.com/djoslin0/sm64ex-coop)
- Resemble is not an sm64ex-coop client and cannot be used as such
- Resemble may have some missing features or bugs, feel free to report or PR them.
