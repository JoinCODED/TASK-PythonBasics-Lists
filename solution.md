```python
'''
1. Create a list named 'favorite_animals' that has four items:
	1. dog
	2. cat
	3. monkey
	4. rabbit

2. After creating the list, replace the item that currently holds the value "rabbit" with another animal. It can be any animal you like.
3. Then using the 'remove' method, remove 'cat' from the list.
4. Using 'append', add an animal that you like.
5. Print the list to test your code

'''

favorite_animals = ["dog", "cat", "monkey", "rabbit"]
favorite_animals[3] = "octowl"
favorite_animals.remove("cat")
favorite_animals.append("kitty")
print(favorite_animals)


'''
1. Complete the first print statement so that the addition of the second and 
third elements is printed to the console.

2. Using List slicing, complete the second print statement so that it displays 
only the last four items in the list.

'''
numbers = [5, 6, 7, 8, 2, 3, 4]

print(numbers[1] + numbers[2])
print(numbers[3:])
```
