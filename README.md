<h5>TIPS TO MASTERING THE ART OF PYTHON.</h5>

# The Python Tutorial¶

<h5>What is python</h5>

Python is an easy to learn, powerful programming language. It has efficient high-level data structures and a simple but effective approach to object-oriented programming. Python’s elegant syntax and dynamic typing, together with its interpreted nature, make it an ideal language for scripting and rapid application development in many areas on most platforms.

The Python interpreter and the extensive standard library are freely available in source or binary form for all major platforms from the Python web site, https://www.python.org/, and may be freely distributed. The same site also contains distributions of and pointers to many free third party Python modules, programs and tools, and additional documentation.

The Python interpreter is easily extended with new functions and data types implemented in C or C++ (or other languages callable from C). Python is also suitable as an extension language for customizable applications.

# Getting Started in Python

The process we use to write software using Python (and most programming languages) is fairly straight forward: To master Python the effective
way, a set of rules/steps needs to be followed to get the most and best possible implementation out of the software to be developed or developed.

<p>Few set of rules and steps are highlighted below to mastering Python the right way</p>

<h1>Learn the Basics</h1>
Skipping the basics of Python is more like building a house without a proper foundation in place, definitely the house is sure definitely to collapse at any estimated point in time.
<li>Basic Syntax</li>
<li>Variables and Data Types</li>
<li>Conditionals</li>
<li>Type Casting, Exceptions</li>
<li>Functions, Builtin Functions</li>
<li>Lists, Tuples, Sets, Dictionaries</li>

To get the most out of Python basics consider the following examples;
    ``
    def test_list_greater():
        list_given = ['10', '35', '34']
        give_a_number = input("Give a number to check >>: ")
    
    if give_a_number > list_given[0]:
        print("The number given is greater than the first number in the list ")
    elif give_a_number > list_given[1]:
        print("The number given is greater than the second number in the list ")
    elif give_a_number > list_given[2]:
        print("The number given is a greater than the third number in the list ")
    else:
        pass
    
    test_list_greater() 
    ``
""" consider the above function, where the name of the function is <b>test_list_greater</b>, the function here tends to check if an entered number is greater than any of the numbers given in the list created named <b>list_given</b>, the <b>give_a_number</b> variable takes in any value because the variable isn't specified for a particular data type, any value entered for this function passes through the conditions specified and if it meets any of the condition specified, the print gives an output of the conditioned satisfied, the <b>test_list_greater()</b> calls the function to be executed."""

<h1>Datastructures and Algorithms</h1>
Mastering a Software Engineer/Software Developer role, the essentials of data structures and algorithms can't be omitted. Layman words of Algorithms involve step by step instructions given to a computer.
<li>Arrays and Linked Lists</li>
<li>Heaps, Stacks and Queues</li>
<li>Hash Tables</li>
<li>Binary Search Trees</li>
<li>Recursion</li>
<li>Sorting Algorithms</li>

To get a full grasp of how data algorithm structure works and implemented, we'll work through the process of another python program 
```
    # a list of unsorted numbers
    unsorted_list = [4, 5, 12, 1, 3, 19, 2]

    #python has a built in fuction that sorts out items accordingly
    print(sorted(unsorted_list))

    '''
        the sorted function automatically sorts items in an orderly arranged manner
    '''

```
let's take a look at a more complex python program for scheduling process
```
    def static_stack():
        stack_object = ["HP", "DELL", "ACER", "LENOVO", "APPLE", "SAMSUNG", "HISENSE"]

    print("List of items in stack are; ")
    for i in range(len(stack_object)):
        print(stack_object[i])

    print("\nList of order of execution for the LAST IN FIRST OUT ALGORITHM will be; ")
    for i in range(len(stack_object)):
        i+=1
        stack_order = stack_object[-i]
        print(stack_order)

    #stack_remaining = stack_order.remove(i)-stack_object[i]
    #stack_remaining = stack_object[-1]
    print("\nItem ", stack_object[-1], " will be out of the stack first.")

    stack_object.remove(stack_object[-1]) 
    #print(stack_object)
    print("Items ramining are: \n")
    for i in range(len(stack_object)):
        i+=1
        #print(stack_object[i])
        print(f" {stack_object[-i]}")


    print("\nItem ", stack_object[5], " will be out of the stack next.")
    #if "SAMSUNG" in stack_object:
    #    print(f" {stack_object}") 

    stack_object.remove(stack_object[5]) 
    
    print("Items ramining are: ")
    for i in range(len(stack_object)):
        i+=1
        #print(stack_object[i])
        print(f" {stack_object[-i]}")

    #get the item to be out of the stack next
    print("\nItem ", stack_object[4], " will be out of the stack next.")

    stack_object.remove(stack_object[4]) 
    
    print("Items ramining are: ")
    for i in range(len(stack_object)):
        i+=1
        #print(stack_object[i])
        print(f" {stack_object[-i]}")

    #get the item to be out of the stack next
    print("\nItem ", stack_object[3], " will be out of the stack next.")

    stack_object.remove(stack_object[3]) 
    
    print("Items ramining are: ")
    for i in range(len(stack_object)):
        i+=1
        #print(stack_object[i])
        print(f" {stack_object[-i]}")


    #get the item to be out of the stack next
    print("\nItem ", stack_object[2], " will be out of the stack next.")

    stack_object.remove(stack_object[2]) 
    
    print("Items ramining are: ")
    for i in range(len(stack_object)):
        i+=1
        #print(stack_object[i])
        print(f" {stack_object[-i]}")

    
    #get the item to be out of the stack next
    print("\nItem ", stack_object[1], " will be out of the stack next.")

    stack_object.remove(stack_object[1]) 
    
    print("Items ramining are: ")
    for i in range(len(stack_object)):
        i+=1
        #print(stack_object[i])
        print(f" {stack_object[-i]}")

    
    #get the item to be out of the stack next
    print("\nItem ", stack_object[0], " will be out of the stack next.")

    stack_object.remove(stack_object[0])
    try:
        if stack_object == []:
            print(f"Stack emptied. Execution terminated")
    except:
        print("Cannot be executed completely.")
    

if __name__ == "__main__":
    static_stack()
```

in the above python example, we looked at a scheduling algorithm process called LAST IN FIRST OUT, the program above gives a simple illustration of how an algorithm works. 
<b>LAST IN FIRST OUT</b> is a scheduling <i>Algorithm</i> that involves attending to and giving priority to processes that arrives last i.e processes that arrives last in the stack are executed first. It is a reverse process of how <b>FIRST IN FIRST SERVE</b> processes are executed.
Get full explantion and write-up on CPU scheduling algorithms using Python here https://medium.com/@oladapomiracle/cpu-scheduling-algorithm-demonstration-using-python-67c986537e64.

<h1>Advanced Topics</h1>
<li>Iterators</li>
<li>RegEx</li>
<li>Decorators</li>
<li>Lambdas</li>
<li>List Comprehensions</li>
<li>Generator Expressions</li>
<li>Paradigms</li>

OOP - Object Oriented Programming
    <li>Classes</li>
    <li>Inheritance</li>
    <li>Methods, Dunder</li>

Modules
    <li>Builtin</li>
    <li>Custom</li>

    ```
        python has built-in and custom modules, each of which has their functions defined attributes on what to do. Modules are a way of writing python programs that can be called in another python program for execution. For example, 
            
            def add(x, y):      
            """a function to perform an addition operation needs not to be define in another python program file, but can just be simply   called by importing this saved python addition function i.e import addition or from addition import add"""
                return x + y
        
        custom modules are also developed using this method explained above, but can be complicated at times, and you definitely want to save yourself the stress of writing your own custom modules when there are already custom made deployed for the same need you want them for just for you to install them using the Python PIP.
    ```

Package Managers
    <li>PyPI</li>
    <li>PIP</li>
    <li>Conda</li>

GUI - Graphical User Interface
    <li>Tkinter</li>
    <li>Custom tkinter</li>

<h1>Learn a Framework</h1>
<li>Synchronous</li>
    <li>Django</li>
    <li>Flask</li>
    <li>Pyramid</li>

<li>FastAPI</li>

<li>Asynchronous</li>
    <li>gevent</li>
    <li>aiohttp</li>
    <li>Tornado</li>
    <li>Sanic</li>

<h1>Testing your Apps</h1>
<li>doctest</li>
<li>nose</li>
<li>pytest</li>
<li>unittest / pyUnit</li>

<h1>Build Softwares</h1>
<p>Project Ideas for development</p>
<li>Solving a problem YOU have/identify with. This is always going to be the best project because YOU know the details of why this problem exists. You can talk with confidence about this because you know the ins and out of this!</li>

<li>Auto repair store inventory tracker that has an algorithm that reordes product BEFORE it runs out of stock based on the usage of the mechanics. This can not be a static number because a shop will use more oil filters on a regular basis than it would use transmissions. This should also have a dashboard for the "owner" to see graphs showing parts usage. Are you only focusing on backend? Then create the inventory system for the store without the front end but in CLI(command line )</li>

<li>Creating a project with a government API where you are using the data and statistics to showcase it in a professional use case.</li>

<li>A plumber repair booking application that can show the plumber financials for their business.</li>

<li>A medication tracker that helps remind forgetful people to take their medicine but also solves the problem of over medicating by creating alerts for user to actually log their intake of the medicine.</li>