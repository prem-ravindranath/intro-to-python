# Intro to Python

You have the following data:
| Name          | Location      | Subjects |
| ------------- |:-------------:| --------:|
| todd | melbourne | physics |
| jamie | toronto | physics |
| rebecca | Los Angeles | maths |
| michael | Sydney | biology |
| vincent | toronto | chemistry |
| georgia | Melbourne | stats |
| allen | toronto | chemistry |
| sarah | auckland | chemistry |

To get started, add the following lines of code to the top of your Python script:
```python
import pandas
data = pandas.read_csv("https://raw.githubusercontent.com/kasun-maldeni/intro-to-python/master/data.csv")
print(data)
```

## Questions
1. Print out the first row of data in a string in the following format: "Todd studies Physics in Melbourne".
2. Do question 1 for EVERY row of data i.e. for each student.
3. Print out the names of all the students studying in toronto.
4. Do question 3 for all the students in Melbourne.
5. Print out all the students who are taking the same courses in the following format: "Todd and Jamie are taking Physics. Vincent and Allen and Sarah are taking Chemistry." etc.
