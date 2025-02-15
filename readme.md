## Setup

1. `which python3` should say `/opt/homebrew/bin/python3`

1. `python3 --version` should say `Python 3.13.2`

1. `HTTP_PROXY` and `HTTPS_PROXY` are `''`

1. Create a new venv: `python3 -m venv .venv`

1. Activate it: `source .venv/bin/activate`

1. Install required stuff: `pip install cryptography torch transformers peft datasets ipykernel python-dotenv`
