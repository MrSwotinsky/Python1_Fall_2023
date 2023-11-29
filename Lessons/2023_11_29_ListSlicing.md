## Python 1
Wednesday, November 29th 2023<BR>

### **List Slicing**

**AIM:** In what ways can we leverage list slicing to develop programs in Python?

**OUTCOME ALIGNMENT:**

<ins>IEC.TYS63T.1</ins>: Write and analyze programs in relation to **data collections**.
<br><ins>IEC.TYS63T.6</ins>: **Communicate** effectively as a computer scientist.

**SUCCESS CRITERIA:**

- [ ] I can use code tracing to determine a slice of a list given any of the following:
    - [ ] `my_list[a:b]`
    - [ ] `my_list[a:]`
    - [ ] `my_list[:b]`
    - [ ] `my_list[:]`
- [ ] I can explain, in my own words, why a given slice results in a given list.
- [ ] I can delete a slice from a list.
        
##

**DO NOW:**  Load up your virtual environment.  While it is loading up...

1. On a piece of paper, write down a list containing at least 5 items.
2. Write down a sub-list of your original list by removing one or more elements from the beginning, end or both of your original list.
3. Write down a new list containing at least 5 items.
4. Write down a new sub-list by removing two or more consecutive elements from your list (not including the first or last elements.)
   
**AGENDA:**  

* Lists slices in real life.
* List Slices (code a-long)
    * Slices of the forms, `my_list[a:b]`, `my_list[a:]`, `my_list[:b]`, and `my_list[:]`.
    * Negative indices.
    * Empty slices.
* Lab: List Slices (see below).
* Summary / Share
  
**LAB - LIST SLICES:**

1. Generate a list containing at least 10 elements and assign it to an appropriately named variable.  Then, display the slice.
2. Using positive indices, generate a slice of your list containing all elements from index 2 to index 8 (including the elements at indices 2 and 8 themselves) and assign it to an appropriately named variable.  Then, display the slice.
3.  Generate the same slice of your list, but instead of using positive indices, use negative indices.  Then, display the slice.
4.  Use the slicing method to generate a copy of your list and assign it to an appropriately named variable.  Then, display the slice.
5.  Generate an empty slice of your list and assign it to an appropriately named variable.  Then display the slice.
6.  Use the slicing method to delete all elements from index to index 8 (including the elements at indices 2 and 8 themselves).  Then display your list.


**HOMEWORK:** Upload List Slices lab your GitHub portfolio.  Remember to use an appropriate naming convention.

##

**REFERENCE:**
| Code | Description | 
|---|---|
|`my_list[a:b]`|Generates a slice starting with the element at index `a` and ending with the element at index `b-1`.<br><br>**Notes:** <br>If `a` is out of range (on the left), the slice will begin with the element at index `0`.<br><br>If `b-1` is out of range (on the right), the slice will end with the last element of the list.<br><br>If both `a` and `b` are out of range, the slice will be an empty list.<br><br>If `b` is less than or equal to `a`, the slice will be an empty list.|
|`my_list[a:]`|Generates a slice starting with the element at index `a` and ending with the last element of the list.<br><br>**Note:** <br>If `a` is out of range (on the left), the slice will begin with the element at index `0`.<br><br>If `a` is out of range(on the right), the slice will be an empty list.|
|`my_list[:b]`|Generates a slice starting with the element at index `0` and ending with the last element of the list.<br><br>**Note:** <br>If `b-1` is out of range (on the right), the slice will end with the last element of the list.<br><br>If `b-1` is out of range (on the left), the slice will be an empty list.|
|`my_list[:]`|Generates a slice that is a copy of the list.<br><br>**Note:** <br>This is a great way to generate a copy of a list instead of a pointer.|
|`del my_list[a:b]`<br>OR<br>`del my_list[a:]`<br>OR<br>`del my_list[:b]`<br>OR<br>`del my_list[:]`|Deletes a slice from a list.|

**READING:** https://edube.org > Python Essentials 1 > 3.6.1.2 - 3.6.1.5
