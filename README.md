# WheePython (wheepy)

wheepy is a Python package for running the [Whee Programming Language](https://github.com/NarpLang/whee) using Python.

## Installation

### Requirements:
- `git`
- `python3` (version 3.x)
- `python3-pip`
- `python3-venv`

### Steps:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/NarpLang/wheepy.git
    cd wheepy
    ```

2. **Create and activate a virtual environment:**
    ```bash
    python3 -m venv wheepy-venv
    source wheepy-venv/bin/activate  # On Windows, use `wheepy-venv\Scripts\activate`
    ```

3. **Install the package:**
    ```bash
    pip install .
    ```

Or you can run it in a single chain like this:

```bash
git clone https://github.com/NarpLang/wheepy.git && cd wheepy && python3 -m venv wheepy-venv && source wheepy-venv/bin/activate && pip install .
