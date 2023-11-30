## Python 1
Thursday, November 30th 2023<BR>

### **Lists and Control Flow**

**AIM:** In what ways can we leverage control flow and lists together to develop programs in Python?

**OUTCOME ALIGNMENT:**

<ins>IEC.TYS63T.3</ins>: Write and analyze programs in relation to **control flow**.
<br><ins>IEC.TYS63T.4</ins>: Write and analyze programs in relation to **data collections**.
<br><ins>IEC.TYS63T.6</ins>: **Communicate** effectively as a computer scientist.

**SUCCESS CRITERIA:**

- [ ] I can use a for loop to iterate through and perform actions on each element of a list.
- [ ] I can use a conditional to make decisions about what action to perform on each element of a list based on whether or not it meets a given condition.
        
##

**DO NOW:**  Load up your virtual environment.  While it is loading up...

1. On a piece of paper, write down a list containing containing holiday gifts.
2. Write down a way to split your list into two categories.  You choose the categories.  Some examples include:
    * Gifts you plan to give vs. gifts you hope to receive.
    * Clothing vs. other types of gifts.
    * Budget gifts vs. expensive gifts.
3. Write down two new lists...one for each category you chose.
   
**AGENDA:**  

* Control flow and lists in real life.
* Iterating through lists (code a-long)
* Conditionals and lists (code-a-long)
* Lab: https://edube.org > Python Essentials 1 > 3.4.1.13
* Summary / Share (collaborative problem solving)

**HOMEWORK:** Upload lab 3.4.1.13 GitHub portfolio.  Remember to use an appropriate naming convention.

##

**REFERENCE:**

**Iterating through a list:** The following code snippet will iterate through every element in `my_list` and perform some action.

```python
for my_element in my_list:
    PERFORM SOME ACTION
```

Example 1/ The following code snippet will display every product in `inventory`:

```python
for product in inventory:
    print(product)
```

Example 2/ The following code snippet will discount every price in `prices` by 10%:

```python
for price in prices:
    price *= -.1
```

**Conditionals and lists:** The following code snippet will iterate through every element in`my_list` and, if the element meets a certain condition, perform some action. 

```python
for my_element in my_list:
    if CONDITION:
        PERFORM SOME ACTION
```

Example 3/ The following code snippet will display every even number in `numbers`:

```python
for num in numbers:
    if num % 2 == 0:
        print(num)
```

Example 4/ The following code snippet will generate a new list, `a_names` and append every name that in `names` that starts with an a to `a_names`:

```python
a_names = []
for name in names:
    if name[0] == "A" or name[0] == 'a':
        a_names.append(name)
```

**READING:** https://edube.org > Python Essentials 1 > 3.4.1.9 - 3.4.1.13
