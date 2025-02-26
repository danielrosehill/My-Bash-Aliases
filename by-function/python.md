# Useful aliases for Python development


alias venv='python3 -m venv .venv && source .venv/bin/activate'
alias py='python3'  # Shorthand for running Python 3
alias vca='python3 -m venv .venv && source .venv/bin/activate && if [ -f requirements.txt ]; then pip install -r requirements.txt; fi'
alias activate='source .venv/bin/activate'
alias vreq="pip freeze > requirements.txt"
alias vin="pip install -r requirements.txt"
alias vupgrade="pip install --upgrade -r requirements.txt"
