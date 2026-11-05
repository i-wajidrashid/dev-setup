
# dev-setup

This repository contains `setup.sh`, a bash script that automates setting up my development environment on Ubuntu after a fresh install or system wipe.

## What the script does
1. Updates the APT package list.
2. Installs essential development tools: `git`, `curl`, `jq`, `python3-venv`, and `mysql-client`.
3. Configures my global Git username and email address.

## How to run it
1. Clone this repository and move into the folder:
   git clone git@github.com:i-wajidrashid/dev-setup.git
   cd dev-setup

2. Make the script executable:
   chmod +x setup.sh

3. Run the script:
   ./setup.sh
