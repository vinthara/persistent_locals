# persistent_locals

1) Run the python script : 
```
python3 -i main.py
```
2) Inspect function :

```
>>> test_sum()
7
>>> test_sum.locals
{'i': 1, 'a': 2, 'b': 5, 'df':    0
0  a
1  b}
>>> test_sum.locals["df"]
   0
0  a
1  b
>>>
```