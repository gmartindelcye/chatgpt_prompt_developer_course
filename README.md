
# ChatGPT Prompt Engineering for Developers

https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/


## Setup

1. Copy env-example to .env:

    $ cp env-example .env


2. Obtain your API_KEY from openai.com and substitute the one in the `.env` file. The existing in the file is a fake one and does not work.


3. Create an virtual environment:

    $ python3 -m venv .venv


4. Activate virtual environment:

    $ source .venv/bin/activate


5. Install needed libraries with pdm (https://pdm.fming.dev/latest/):

    $ pdm install


6. Use vscode with jupyter notebook extension, or jupiter lab to run the notebooks