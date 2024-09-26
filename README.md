# Python Course

Python is a general-purpose programming language created by **Guido van Rossum** in 1991.

### Python is useful for a variety of purposes:
- Web Development
- Automation
- Data Analysis
- Scripting
- Software Development
- Software Testing
- Mathematics
### WHY PYTHON
- Its simple to learn
- one can achieve more by writing few codes of lines
- its interpreted ,its doesnot require interpreter
- its support procedural language,functional and object oriented programming language
python has two version python2 and python3 ,python3 is the recomended version because of updates
### to check if python exists and version of python 
python --version
## To interact with output
we use print function() followed by either single qoute or double qoute to output information on python file.

`print("hello ,world" )`

`print("hello, my name is silas" )`

`print("hello ,am learning python )`

print(3) #numbers are not enclosed in qoutation unless you want to ouput as string

## comments in python
- comments : allows you to describe what your program is doing
  
or

- what some part of code mean 

or 
- put some kind of meaning to your code 

commenst can be written as single line comment or double line comment
## single line comment

single line comment use #

#this is a single line comment

`print("what is python programming")`


## multiline comment


multine line comment use single tripe qoute or double triple qoute


"""
`print("hello ,today am learning python programming")`
"""


## variables

variable are containers which are used to store data or some information

example

- name='silas sakwa'
age=67
country ="kenya"

- name is a variable that stores information about silas

- age=67 age is a vraiable that stores the age 67
country is a variable that store kenya

we can use print function() to output the value of variables

example
name="silas sakwa"

`print(name)'
``` output
silas
```

example 2
```
customer="Kate"

product="Iphone 3"

price=100000

print(customer)

print(prouct)

print(price)

```

output

```kate```

```iphone 3```

```100000```


## let learn how to output using formatted output


```
customer="Kate"

product="Iphone 3"

price=100000
```

``` print(f"Customer name:{} product purchased{} at ksh {}".format(customer,product,price)```

output

```customer name Kate product purchased Iphone 3 at ksh 100000 ```

another way of printing formated output is using concatation means(+)

``` print("Customer name is " +customer)```

``` print("Product is " +product)```

``` print("price  " +price)```

``` print("Price " +  str (price))```

## Typecasting
used to know type of data stored in a container

also used to change a value of a variable from one state to another

- customer_name="Kate"

- Prodcut_Pucharsed="Itel 05"

- price=10000

- height=11.7

```print(type(height))```

-- output

float

```print(type(customer_name))```

-- output

str

```print(type(price))```

-- output

price


- int () converts any value to integer

- float () converts any vlaue to float

- str () convert any value to string

## scope of variable

it refers to where a variable is stored

- global variable :A variable decared and can be accessed anywhere

- local variable :variable decalred but can only be accessed where its declared


## Data types

Data type is  kind of data that can be stored and manipulated in a program

example

- Text:String c"silas sakwa", "Engineering" ,"Kenya" ,"1000","software"

- Numeric type :
  
Integer (3,5,1000,56,255,1000000)

float(3005.9, 45.6 ,800.3)

 Complex(5j)

- sequence :list ,tuple ,range

- mapping :Dictionary 

- Set :Set

- Boolean :Boal


  ## string

  a string is a group of characters enclosed in double qoute or single qoute

  example

  name="silas sakwa"

```print(name)```

the output will be

```silas sakwa ```
## operation on strings 

### To find the lenght of the string


```name = "Alice"  ```


```length = len(name)  #Get the length of the string```


output

```print(name + " has " + str(length) + " characters.")```# Alice has 5 characters

### to uppercase


```name="silas sakwa ```

```print(name.uppercase())```

output

```SILAS SAKWA```#The name has been converted to uppercase



### replace string

replace_this_name=name.replace("S","C")



## String slicing

```name="silas sakwa"```


```print(name[0])```

-This will print the first character of the string

```s```


