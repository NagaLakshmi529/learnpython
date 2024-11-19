# learnpython

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
