#  Data Science Foundations - Codecademy Learning Path 
This repo contains personal projects done as a part of the  “Data Science Foundations” Codecademy learning path.
## Life-Expectancy-and-GDP Project
- The goal of the "Life-Expectancy-and-GDP" project is to analyze data on `GDP` and `Life Expectancy` from the World Health Organization and the World Bank to try and identify the relationship between the `GDP` and `Life Expectancy` of six countries over 2000-2015 years.
- Project installation:
    - Create a virtual environment:
        - This command creates a venv in the specified directory and copies pip into it as well. If you’re unsure what to call the directory: .venv is a commonly seen option.
        ```python -m venv <directory>```
    - Activate the created virtual environment:
        - On Linux and MacOS, we activate our virtual environment with the source command. If you created your venv in the myvenv directory, the command would be:
        ```
           #In zsh
           source myvenv/bin/activate
        ```
        ``` 
           #In cmd.exe 
           env\Scripts\activate.bat
           #In PowerShell
           venv\Scripts\Activate.ps1
        ```     
    - Install the ipython kernel while virtual environment activated, name will be displayed in jupyter notebook under kernel.
        ```
            #In zsh
            pip install ipykernel
            python -m ipykernel install --user --name=new_kernel_name
        ```
    
    - Install the dependencies contained in the requirement.txt file
        ```
            #In zsh
            pip install -r requirements.txt
        ```
    - Open a jupyter notebook
         ```
             #In zsh
             jupyter notebook
         ```