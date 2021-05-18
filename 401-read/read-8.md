# List Comprehensions in Python

Fill old list on new list using for loop and append :
```
new_list = []
for i in old_list:
  if filter(i):
  new_list.append(expressions(i)) 

```

There is a better and shorter way to do the same things using using list comprehension :
`new_list = [expression(i) for i in old_list if filter(i)] `

**new_list** : The new list (result).
**expression(i)** : Expression is based on the variable used for each element in the old list
You can use a function as expression that take I as parameter and return a processing value .
**if filter(i)** : Apply a filter with an If-statement.

Example 1 :
```
new_list = []
old_list = [1,2,3,4,5,6]
new_list = [i*10 for i in old_list if i%2==0]
print(new_list)
```
>>> result : `[20,20,60]`

Example 2 : 
convert lower case array to upper case letters inside new array :

`[x.lower() for x in ["A","B","C"]]`

>>> result : `['a', 'b', 'c'] `

