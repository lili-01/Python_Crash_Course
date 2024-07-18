Chapter 4 Working with Lists
In this chapter we learned about looping. Looping allows you to take the same action or set of actions with every item in a list. 

# 4.1: Pizzas
## Think of at least three kinds of your favorite pizza. Store these pizza names in a list, and then use a for loop to print the name of each pizza.
* Modify your for loop to print a sentence using the name of the pizza, instead of printing just the name of the pizza.For each pizza, you should have one line of output containing a simple statement like I like pepperoni pizza. 
* Add a line at the end of your program, outside the for loop, that states how much you like pizza. The output should consist of three or more lines about the kinds of pizza you like and then an additional sentence, such as I really love pizza!

## Code:
```
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


