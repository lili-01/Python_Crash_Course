Chapter 4 Working with Lists
In this chapter we learned about looping. Looping allows you to take the same action or set of actions with every item in a list. 

# 4-1: Pizzas 🍕
## Think of at least three kinds of your favorite pizza. Store these pizza names in a list, and then use a for loop to print the name of each pizza.
* Modify your for loop to print a sentence using the name of the pizza, instead of printing just the name of the pizza.For each pizza, you should have one line of output containing a simple statement like I like pepperoni pizza. 
* Add a line at the end of your program, outside the for loop, that states how much you like pizza. The output should consist of three or more lines about the kinds of pizza you like and then an additional sentence, such as I really love pizza!

## Code:
```python
#creating a list called pizzas
pizzas=['Hawaiian', 'Margherita','Mushrooms']

#print out all pizza names
for pizza in pizzas:
    print(pizza)
print("\n")
#Here we print out pizza names in a sentence
for pizza in pizzas:
    print(f"I like {pizza} pizza!")

print("I'm obssesed with pizza!")
```
## Output: 
![image](https://github.com/user-attachments/assets/99b2139a-cba4-4f15-a87e-8fb778c4c761)



# 4-2: Animals 🐶
## Think of at least three different animals that have a common characteristic. Store the names of these animals in a list, and then use a FOR loop to print out the name of each animal. 
* Modify your program to print a statement about each animal such as  *A dog would make a great pet*.
* Add a line at the end of your program stating what these animals have in common. You could print a sentence such as *Any of these animals would make a great pet*!
## Code:
```python
#created list called animals that store different animal elements
animals=['dog','cat','bunny']
# in this for loop we are looping thru each element and printing out a statement
for animal in animals:
    print(f"A {animal} would make a great pet!")
#Here we create a new line 
print()
#this outside the FOR loop in which it displays a statement
print("Any of these animals would make a cute pet!")   

```
## Output: 

![image](https://github.com/user-attachments/assets/d6b35436-f24f-4311-a02c-3911c72e80a3)

# 4-3 Counting to Twenty:
## Use a for loop to print the numbers from 1 to 20, inclusive.

## Code:

```python
# using a for loop and range to print out numbers from 1-20
for value in range(1,21):
    print(value)

```
## Output
![image](https://github.com/user-attachments/assets/3daf452d-8ce6-4054-8a38-c9e8b25e05e3)

# 4-4: One Million:
## Make a list of the numbers from one to one million, and then use a for loop to print the numbers (if the output is taking too long, stop it by pressing CRTL-C or by closing the output window.)
## Code:
```python
for value in range(1,1000001):
    print(value)
```
## Output:
![image](https://github.com/user-attachments/assets/72e2bfa2-36f1-40a0-9b8a-212c07b98f7d)



# 4-5: Summing a million
## Make a list of the numbers from one to one million, and then use min() and max() to make sure your list actually starts at one and ends at one million. Also, use the sum() function to see how quickly Python can add a million numbers.
## Code:
``` python
numbers = list(range(1, 1000001))

print(min(numbers))
print(max(numbers))
print(sum(numbers))
```
## Output:
![image](https://github.com/user-attachments/assets/d231da71-88f1-4530-8162-75fbdaa430e0)

# 4-6: Odd Numbers
## Use the third argument of the range() function to make a list of the odd numbers from 1 to 20. Use a for loop to print each number.
## Code:
```python
odd_numbers = []
for value in range(1, 21, 2):
    odd_numbers.append(value)

print(f"List of odd numbers: {odd_numbers}")

```
## Output:
![image](https://github.com/user-attachments/assets/0c8552c4-f6b4-463a-b6ed-2986c1072b94)

