# emp_attrition

the code is running via a virtual env

to make a virtual env

    mac
    python3 -m venv venv

    windows
    python -m venv venv

to activate the env type in the terminal

    mac
    source venv/bin/activate

    windows
    venv\Scripts\activate

to run any file use
python <file.py>

Once you install more packages using pip remember to add files into requirements.txt
use the command

    pip freeze > requirements.txt

to install all the requirements use

    pip install -r requirements.txt

to run the file

    streamlit run main.py
