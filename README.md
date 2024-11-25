# Housing Sales in King County, Washington

This project is centered around exploratory data analysis techniques. I used the the King County Housing Data: This dataset contains information about home sales in King County (USA). It is a predominantly urban and suburban county. Through EDA/statistical analysis above I came up with the overall data.

There is more information about the county here: https://de.wikipedia.org/wiki/King_County_(Washington)

In addition I also came up with three recommendations for my client Jennifer Montgomery, who wants to buy a house in the King County Area.

## Requirements

- pyenv
- python==3.11.3

## Set up your Environment
This repo contains a `requirements.txt` file with a list of all the packages and dependencies you will need.

Before you can start with plotly in Jupyter Lab you have to install node.js (if you haven't done it before).
- Check **Node version**  by run the following commands:
    ```sh
    node -v
    ```
    If you haven't installed it yet, begin at `step_1`. Otherwise, proceed to `step_2`.


### **`macOS`** type the following commands : 


- `Step_1:` Update Homebrew and install Node by following commands:
    ```sh
    brew update
    brew install node
    ```

- `Step_2:` Install the virtual environment and the required packages by following commands:

    ```BASH
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/bin/activate
    pip install --upgrade pip
    pip install -r requirements.txt
    ```
### **`WindowsOS`** type the following commands :


- `Step_1:` Update Chocolatey and install Node by following commands:
    ```sh
    choco upgrade chocolatey
    choco install nodejs
    ```

- `Step_2:` Install the virtual environment and the required packages by following commands.

   For `PowerShell` CLI :

    ```PowerShell
    pyenv local 3.11.3
    python -m venv .venv
    .venv\Scripts\Activate.ps1
    pip install --upgrade pip
    pip install -r requirements.txt
    ```

    For `Git-Bash` CLI :
  
    ```BASH
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/Scripts/activate
    pip install --upgrade pip
    pip install -r requirements.txt
    ```


`Note:` If you encounter an error when trying to run pip install --upgrade pip, try using the following command:
```
