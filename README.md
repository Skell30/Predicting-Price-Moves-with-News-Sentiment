 # Pridicting price moves with news sentiment

## 💻 Development Setup

### 1. Clone the repository
`bash
git clone https://github.com/Skell30/Predicting-Price-Moves-with-News-Sentiment
cd Predicting-Price-Moves-with-News-Sentiment

# venv
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt


C:
├───.github
│   └───workflows
├───.vscode
├───notebooks
├───scripts
├───src
├───tests
└───venv
    ├───Include
    ├───Lib
    │   └───site-packages
    │       ├───pip
    │       │   ├───_internal
    │       │   │   ├───cli
    │       │   │   │   └───__pycache__
    │       │   │   ├───commands
    │       │   │   │   └───__pycache__
    │       │   │   ├───distributions
    │       │   │   │   └───__pycache__
    │       │   │   ├───index
    │       │   │   │   └───__pycache__
    │       │   │   ├───locations
    │       │   │   │   └───__pycache__
    │       │   │   ├───metadata
    │       │   │   │   ├───importlib
    │       │   │   │   │   └───__pycache__
    │       │   │   │   └───__pycache__
    │       │   │   ├───models
    │       │   │   │   └───__pycache__
    │       │   │   ├───network
    │       │   │   │   └───__pycache__
    │       │   │   ├───operations
    │       │   │   │   ├───build
    │       │   │   │   │   └───__pycache__
    │       │   │   │   ├───install
    │       │   │   │   │   └───__pycache__
    │       │   │   │   └───__pycache__
    │       │   │   ├───req
    │       │   │   │   └───__pycache__
    │       │   │   ├───resolution
    │       │   │   │   ├───legacy
    │       │   │   │   │   └───__pycache__
    │       │   │   │   ├───resolvelib
    │       │   │   │   │   └───__pycache__
    │       │   │   │   └───__pycache__
    │       │   │   ├───utils
    │       │   │   │   └───__pycache__
    │       │   │   ├───vcs
    │       │   │   │   └───__pycache__
    │       │   │   └───__pycache__
    │       │   ├───_vendor
    │       │   │   ├───cachecontrol
    │       │   │   │   ├───caches
    │       │   │   │   │   └───__pycache__
    │       │   │   │   └───__pycache__
    │       │   │   ├───certifi
    │       │   │   │   └───__pycache__
    │       │   │   ├───chardet
    │       │   │   │   ├───cli
    │       │   │   │   │   └───__pycache__
    │       │   │   │   ├───metadata
    │       │   │   │   │   └───__pycache__
    │       │   │   │   └───__pycache__
    │       │   │   ├───colorama
    │       │   │   │   ├───tests
    │       │   │   │   │   └───__pycache__
    │       │   │   │   └───__pycache__
    │       │   │   ├───distlib
    │       │   │   │   └───__pycache__
    │       │   │   ├───distro
    │       │   │   │   └───__pycache__
    │       │   │   ├───idna
    │       │   │   │   └───__pycache__
    │       │   │   ├───msgpack
    │       │   │   │   └───__pycache__
    │       │   │   ├───packaging
    │       │   │   │   └───__pycache__
    │       │   │   ├───pkg_resources
    │       │   │   │   └───__pycache__
    │       │   │   ├───platformdirs
    │       │   │   │   └───__pycache__
    │       │   │   ├───pygments
    │       │   │   │   ├───filters
    │       │   │   │   │   └───__pycache__
    │       │   │   │   ├───formatters
    │       │   │   │   │   └───__pycache__
    │       │   │   │   ├───lexers
    │       │   │   │   │   └───__pycache__
    │       │   │   │   ├───styles
    │       │   │   │   │   └───__pycache__
    │       │   │   │   └───__pycache__
    │       │   │   ├───pyparsing
    │       │   │   │   ├───diagram
    │       │   │   │   │   └───__pycache__
    │       │   │   │   └───__pycache__
    │       │   │   ├───pyproject_hooks
    │       │   │   │   ├───_in_process
    │       │   │   │   │   └───__pycache__
    │       │   │   │   └───__pycache__
    │       │   │   ├───requests
    │       │   │   │   └───__pycache__
    │       │   │   ├───resolvelib
    │       │   │   │   ├───compat
    │       │   │   │   │   └───__pycache__
    │       │   │   │   └───__pycache__
    │       │   │   ├───rich
    │       │   │   │   └───__pycache__
    │       │   │   ├───tenacity
    │       │   │   │   └───__pycache__
    │       │   │   ├───tomli
    │       │   │   │   └───__pycache__
    │       │   │   ├───truststore
    │       │   │   │   └───__pycache__
    │       │   │   ├───urllib3
    │       │   │   │   ├───contrib
    │       │   │   │   │   ├───_securetransport
    │       │   │   │   │   │   └───__pycache__
    │       │   │   │   │   └───__pycache__
    │       │   │   │   ├───packages
    │       │   │   │   │   ├───backports
    │       │   │   │   │   │   └───__pycache__
    │       │   │   │   │   └───__pycache__
    │       │   │   │   ├───util
    │       │   │   │   │   └───__pycache__
    │       │   │   │   └───__pycache__
    │       │   │   ├───webencodings
    │       │   │   │   └───__pycache__
    │       │   │   └───__pycache__
    │       │   └───__pycache__
    │       └───pip-24.0.dist-info
    └───Scripts


python --version
