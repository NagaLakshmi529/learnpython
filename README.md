# learnpython

# Printing the format of the output:
**a)Using f-string**
print(f"{s} * {i} =", s*i) //5*1=5 ....5*10=50
**b)Using format()**
print("{} * {} =".formate(s,i)
# Unpacking the elements in list has 2 ways:
**a) using "*" with print()**
1.To unpack the elements in the list: *s // s=[1,2,3,4,5] print(*s) o/p: 1,2,3,4,5 
2.To unpack the elements in the list with no space: print(*s,sep='') o/p: 12345
The sep='' argument in print() specifies that there should be no separator between the elements (i.e., no spaces).
**b)Using join() and map()**
Convert all elements to strings and join them without any spaces or brackets
result = ''.join(map(str,s))

# any() and all()
any(): Returns True if any element in the iterable is True; otherwise, returns False.
all(): Returns True if all elements in the iterable are True; otherwise, returns False.

# Strings,Tuple,List and Dictionaries are mutable or immutable
**a) String:** it is immutable i.e can not modified once assigned eg. s="Hello";s[0]="h" o/p: it throws error
**But** indirectly you can change the strings using list. s="Hello";s="h" + s[1:] 0/p: hello here s[1:] gives "ello"

**b)Tuple: **tuples are Immutable and it cann't change .You cannot modify an individual element of a tuple.
t = (1, 2, 3);t[0] = 10  # This will raise a TypeError because tuples are immutable
However, if the tuple contains mutable elements (like a list), you can modify the mutable element inside the tuple:
t = ([1, 2], 3);t[0][0] = 10  # This is allowed because the list inside the tuple is mutable; print(t)  # Output: ([10, 2], 3)

c)Dictionaries: Mutable
Methods:
•a.items(): Returns a list of (key,value)tuples.
•a.keys(): Returns a list containing dictionary's keys.
•a.update({"friends":}): Updates the dictionary with supplied key-value pairs.
•a.get("name"): Returns the value of the specified keys (and value is returned eg."harry" is returned here).

d)List: Mutable-can change
Methods:
l1.sort(): updates the list to [1,2,7,8,15,21]
•l1.reverse(): updates the list to [15,21,2,7,8,1]
•l1.append(8): adds 8 at the end of the list
•l1.insert(3,8): This will add 8 at 3 index
•l1.pop(2): Will delete element at index 2 and return its value.
•l1.remove(21): Will remove 21 from the list.


**Strip() ** only removes characters (typically whitespace) from the start and end of a string, but does not modify or break up the content in the middle.
**split() ** breaks a string into a list of substrings based on a delimiter (whitespace or specified character) and removes that delimiter in the process.
