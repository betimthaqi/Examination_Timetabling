
## Examination Timetabling using Integer Linear Programming
![PyPI license](https://img.shields.io/pypi/l/ansicolortags.svg)
![made-with-python](https://img.shields.io/badge/Made%20with-PuLP-1f425f.svg)
<br>This model is based on Integer Linear Programming and is tested using real data from the Faculty of Electrical and Computer Engineering of Prishtina. The model is designed for both types of exam timetabling, regular and irregular, which are basically the same but different in some elements. The model contains several data sets and parameters as entry data and hundreds of thousands of possible combinations between the entry data. Using the PuLP library of the Python programming language the model find us an optimal solution suitable for students and professors or informs us that there is no feasible solution.
##  Project Structure
- `Datasets/` - Input datasets for the model
- `Model/`- The model
- `Output/` - Results of the model
##  Model Execution
**Step 1:** Download [Python](https://www.python.org/downloads/) <br>
**Step 2:** Install Jupyter Notebook
```
pip install notebook
```
**Step 3:** Install Python packages
```
pip install pandas
```
```
pip install pulp
```
**Step 4:** Download model in a specific folder in your local machine and move to that folder
```
cd <folder path>
```
**Step 5:** Start the notebook server and open model file.
```
jupyter notebook <notebook filename>
```
**Step 6:** Change file name in the code with your instance file name
>![enter image description here](https://images4.imagebam.com/90/79/fe/MEB2KT4_o.png)
>
See `Datasets/ExampleDataset.xlsx` as example

**Step 7:** Run the model
```
jupyter run notebook.ipynb
```
:warning: Both files, the model and the instance should be in the same directory.
