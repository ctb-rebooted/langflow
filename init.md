# setup venv
uv venv .venv
source .venv/bin/activate  # ❗ macOS/Linux
.venv\Scripts\activate     # ❗ Windows

# make init
make init

# run backend
make backend

# run frontend
make frontend

# run all
make run_cli