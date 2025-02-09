Based python3.13  
Developed on August 25, 2022

# Getting Started
```
pip install -r requirements.txt

python -m venv myenv

#window
source myenv/Scripts/activate

# linux or mac
# source myenv/bin/activate 
```

# Running the code
```
# Refer to the source command in the Getting Started section, activate the myenv environment, and then try.
(myenv) python index.py
```

# Exe Build
```
pyinstaller --onefile --windowed --add-data="resources/*;resources" --add-data "src/*;src" index.py
# and add resources folder into dist folder
```