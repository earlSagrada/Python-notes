# Tips in python
[Create list of logging calculation results](https://github.com/earlSagrada/Python-notes/blob/master/py_tips.md#create-a-new-list-to-log-the-result-of-other-calculation)
## Create a new list to log the result of other calculation
```python
a = [1, 2, 3, 4, 5, 6]
b = []
for i in range(len(a)):
    temp = a[i]*2 +1
    b.append(temp)
print(b)

>> [3, 5, 7, 9, 11, 13]
```
