# Virtual

## Steps to create a virtual environment on Python

1. Create a repository on GITHUB
2. Clone the repository
3. Execute the following command:

```bash
python -m venv <Name>
```

4. Activate virtual environment

```bash
source env/Scripts/activate
```

4.1. Deactivate virtual environment

```bash
deactivate
```

5. Install ipython library

```bash
pip install ipython
```

6. Execute ipython

```bash
ipython
```

7. Show project dependencies

```bash
pip freeze
```

8. Share dependencies

```bash
pip freeze > requirements.txt
```

'Exercise': Escribir un texto con:
    1. asc
    2. colorama 