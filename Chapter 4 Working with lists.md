Chapter 4 Working with Lists
In this chapter we learned about looping. Looping allows you to take the same action or set of actions with every item in a list. 

# 4-1: Pizzas 🍕
## Think of at least three kinds of your favorite pizza. Store these pizza names in a list, and then use a for loop to print the name of each pizza.
* Modify your for loop to print a sentence using the name of the pizza, instead of printing just the name of the pizza.For each pizza, you should have one line of output containing a simple statement like I like pepperoni pizza. 
* Add a line at the end of your program, outside the for loop, that states how much you like pizza. The output should consist of three or more lines about the kinds of pizza you like and then an additional sentence, such as I really love pizza!

## Code:
```python
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

![image](https://github.com/user-attachments/assets/2dc41a55-f732-4c6f-9c50-b15e0b826a13)


