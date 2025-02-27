### TOPSIS-Python

### What is TOPSIS

The Technique for Order of Preference by Similarity to Ideal Solution is a multi-criteria decision analysis method.It is a method of compensatory aggregation that compares a set of alternatives by identifying weights for each criterion, normalising scores for each criterion and calculating the geometric distance between each alternative and the ideal alternative, which is the best score in each criterion

<br>
### How to install this package:
visit https://pypi.org/project/TOPSIS-Saumyaa-101803609/0.0.8/  <br>
or run: <br>
pip install TOPSIS-Saumyaa-101803609==0.0.8  <br>
on your command line <br>
<br>
### How to use this package:

TOPSIS-Saumyaa-101803609 can be run as in the following example:

Usages:
python topsis \<InputDataFile\> \<Weights\> \<Impacts\> \<ResultFileName\>
  <br>
Example:
topsis inputfile.csv “1,1,1,2” “+,+,-,+” result.csv

### In Command Prompt
```
>> topsis_cmd data.csv "1,1,1,1" "+,+,-,+" result.csv
```
<br>

### In Python IDLE:
from topsis_py.topsis import topsis
<br>
topsis('data.csv','1,1,2,2','+,+,-,+','result.csv')

<br>

## Sample dataset (.csv)

Model | Correlation | R<sup>2</sup> | RMSE | Accuracy
------------ | ------------- | ------------ | ------------- | ------------
M1 |	0.79 | 0.62	| 1.25 | 60.89
M2 |  0.66 | 0.44	| 2.89 | 63.07
M3 |	0.56 | 0.31	| 1.57 | 62.87
M4 |	0.82 | 0.67	| 2.68 | 70.19
M5 |	0.75 | 0.56	| 1.3	 | 80.39

<br>

## Output file (.csv)

Model | Correlation | R<sup>2</sup> | RMSE | Accuracy | Topsis score | Rank
------------ | ------------- | ------------ | ------------- | ------------ | ------------- | -----------
M1 |	0.79 | 0.62	| 1.25 | 60.89 | 0.77221 | 2 
M2 |  0.66 | 0.44	| 2.89 | 63.07 | 0.225599 | 5
M3 |	0.56 | 0.31	| 1.57 | 62.87 | 0.438897| 4
M4 |	0.82 | 0.67	| 2.68 | 70.19 | 0.523878 | 3
M5 |	0.75 | 0.56	| 1.3	 | 80.39 | 0.811389 | 1

<br>
