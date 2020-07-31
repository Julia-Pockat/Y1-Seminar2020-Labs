# Datatypes, Variables & Debugging Lab

## Objective: 
In this lab, you will learn about different data types, including `int`, `float`, `str`, and `bool`, and how to use `type()` to determine what data type a variable is, using **Python**.   
Also, you will learn how to assign *values* to **variables**, how to change the *values* of a **variable**, and how to *recognize* **errors** in code!





<img src="https://miro.medium.com/max/1000/1*aNMBIivJppLy2fMRVUSgHA.gif" width=250>
<img width=300 src="https://gotvantage.com/wp-content/uploads/2017/09/abtest.gif">







## Instructions:
> Before we start, make sure to create a new **Repl.it** and call it **"Day 2"**!  
> In **"Day 2"**, edit `main.py` in order to do the lab.

### 1) Datatypes Practice: 

1. Take a look at this table:
    - First row is done as an example!  
    
    **Expression** | **Your Guess** | **Output**
    --- | --- | ---
    `type(259+33)` | Integer | `int`
    `type(259-33.0)` |  | 
    `type(4)` |  | 
    `type('4')` |  | 
    `type('four')` |  | 
    `type(5/2.0)` |  |
    `type(12 > 2*5)` |  | 
    `type(color + 3)` |  |
    `type('color'*4)` |  | 

1. Go over each line, and try to guess what each line returns as an **output**!
    - If you don't think **Python** can do something, write `Error`.  

1. Now, after you're done guessing, let's put your theories to the test!
    - Try each line in **Repl.it** and understand why it is what it is.
    - If you don't understand something specific, try and ask a classmate first :)

---
### 2) Variables Switch: 
1. In `Repl`, *copy/paste* the following code:  
```python
name = "New York"
age = "Lyel"
hometown = 24
```

2. Your objective is to match the variable **names** to the variable **values**.
    - You can't touch the 3 lines you have just copy pasted.
    - You are allowed to create your own additional variables as you wish.

---
### 3) Strings : 
1. In the **python editor**, define **a variable** with the following code:  
```python
four = '4'
```

2. What happens when you type:
```python
print(four*3)
```
3. Why did this happen?
    - Try to guess and understand on your own.
    - If you got stuck, try asking a classmate first!

4. Now, set a new variable called `five` and make it equal to the integer `4`, and copy this code to your **Repl.it**:
```python
five = 4
print(5)

print(five*3)
```

---
### 4) Debugging Practice: 
Below, you can find 3 mini programs that are written incorrectly.  
We will provide what each program's intention is, and your job is to copy-paste it to your **Repl.it** and fix it!  

1. Intention: Print out `"My name is student"`
```python
my_name = "student"
print("My name is ' + 'my_name")
```  

2. Intention: Print out `"I am 15 years old"`  
```python
my_age = 15
print('I am ' + my_age + 'years old')
```  

3. Intention: Print out the **total score**
```python
score = 4
count = "5"
total = score * count

print(total)
```





##### Great job!
##### Call an Instructor/TA to check your completed tasks
 

If you have extra time, continue to the **Bonus Problems** *below*.  
If not, make sure your code is saved in **Repl.it**!


[![](https://programmer.group/images/article/1a680890c223e534389f27858b5bf33a.jpg)]()





## Bonus Problems: 
1. Think about why you got the errors with some lines. How can you change the line to get no error? Test your guess in the **Repl.it** file! 

2. For the **"Datatypes Practice"**: type all of the lines again without the word `type` at the beginning. What do you get?

3. If you have extra time, complete yesterday's lab(s) if you haven't!


##### Great job on completing the bonus problems section!  
###### Make sure your code is saved in Repl.it


