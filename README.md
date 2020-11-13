# TOPSIS-suryansh-101983044
This python module aims to implement Multiple Criteria Decision Making using TOPSIS ranking.
## Description
This module basically is a function which requires a CSV file as input which contains the model on which you wish to implement TOPSIS  along with impacts,weights and a name for the result file.The model basically builts a result csv file which has two additional columns, TOPSIS score and rank respectively. 
## Installation
Use package manager [pip](https://pip.pypa.io/en/stable/) to install the module.
```bash
pip install TOPSIS-suryansh-101983044
```
## Usage
After intalling the package use the following code:
```python

module =__import__('TOPSIS-suryansh-101983044')

module.topsis(file_name,weights,impacts,resultant_filename)
```
