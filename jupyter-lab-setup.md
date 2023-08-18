# Installing Jupyter Lab

1. You'll need to have both python and pip installed to do this. Ask ChatGPT how if you don't.
2. Open a terminal.
3. Install *jupyterlab*:
```
pip install jupyterlab
```
4. Set up and activate a virtual environment, by running:
```
pip install venv
```
then
```
python -m venv LlamaEnv
```
5. Activate the virtual environment:
- On Mac, run
```
source LlamaEnv/bin/activate
```
- On Windows, run
```
LlamaEnv\Scripts\activate
```
6. Make the virtual environment available to Jupyter Labs with
```
python -m ipykernel install --user --name=llamaEnv
```
7. Start Jupyter with the command
```
jupyter lab
```
8. Menu -> Kernel and select the name of your venv (if not already selected)
9. Menu -> Run -> Run All Cells.
10. Once all cells have run, you'll find the chat interface at the bottom.