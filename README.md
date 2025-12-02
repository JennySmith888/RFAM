# RFAM
Initial work mapping out fast tone amplitude control

# How to Run the Jupyter Notebook

1. Clone the git repo:
```
git clone https://github.com/JennySmith888/RFAM.git
cd /path/to/RFAM/
```

### Python Setup
2. Assuming you have a system install of Python 3, build the Python virtual environment and install the project dependencies
```
python3 -m venv rfam-venv && source rfam-venv/bin/activate && python -m pip install --upgrade pip && python -m pip install -r requirements.txt
```
2.5 (Optional but recommended): Register the Python virtual environment as a Jupyter kernel, so it can be easily selected with a recognizable name by any Jupyter instance (useful if you want to run in VS Code, For Ex.).

```
python -m ipykernel install --user --name rfam --display-name "Python (rfam-venv)"
```

3. Launch Jupyter
```
jupyter lab
```

4. Run the Jupyter Notebook `rfam-demo.ipynb`

