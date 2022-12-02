#  Data Science Foundations - Codecademy Learning Path 
This repo contains personal projects done as a part of the  “Data Science Foundations” Codecademy learning path.
## Life-Expectancy-and-GDP Project
### Objective
The goal of the "Life-Expectancy-and-GDP" project is to analyze data on `GDP` and `Life Expectancy` from the World Health Organization and the World Bank to try and identify the relationship between the `GDP` and `Life Expectancy` of six countries over 2000-2015 years.

### Installation
1. Create a virtual environment:
    ```bash
    $ python -m venv .venv
    ```
    This command creates a venv in the .venv directory.

2. Activate the virtual environment:
* On Linux and MacOS, we activate our virtual environment with the `source` command:
    ```bash
    $ source <directory>/bin/activate
    ```
* On Windows:
    ```bash
    # In cmd.exe
    $ env\Scripts\activate.bat
    # In PowerShell
    $ venv\Scripts\Activate.ps1
    ```

3. Install the dependencies:
    ```bash
    $ pip install -r requirements.txt
    ```

4. Create a new kernel with a desired name:
    ```bash
    $ python -m ipykernel install --user --name=new_kernel_name
    ```

5. Open a jupyter notebook
    ```bash
    $ jupyter notebook
    ```
