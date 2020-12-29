#  PROBLEM SOLVING WITH PYTHON 3 
CONTENTS
 PART 1 :-> PYTHON PROGRAMMING BASICS 
         1.INTRODUCTION TO COLLECTIONS IN PYTHON 
         2.LISTS EXPLAINED IN DETAIL
PART 2 : ALGORITHAMS IN PYTHON 
##### example program 
```sh
```
#####  output


###  INTRODUCTION TO COLLECTIONS IN PYTHON 
#### LIST
list is ordererd collection of elements
we can acess the elements based on the elements
list collection of hetrogeneous data
can have multiple data types in it like dict,list string numbers etc

#### DICTS :
key value pairs
{ke1:value1,key2:value2}
keys can be datypes 
keys are immutable
#### SETS:
SETS are individual objects similar to lists
sets dont allow duplicate values
sets dont have an order and they are random
hence we need to loop or search the element
#### TUPLES:
IMMUTABLE LISTS ARE TUPLES
once declared we cant reassign the value in the tuple
##### example program 
```sh

#list definition with multiple values
my_data = [1,2,"swaroop"]
#acessing the elements in the list
print(my_data[1])
print(type(my_data))
#
my_data_dict ={1:"python",2:"language"}
#to acess the element we should use the key , as its not a good practice to rely on the dict key orders
print(my_data_dict[1])
print(type(my_data_dict))
#set declaration
my_data_set={1,1,1,2,2,2}
print(my_data_set)
#tuple
my_data_tuple =(1,2,"swaroop")
print(my_data_tuple[1])
#once initialized we cant change the item cant be ressagined
```
#####  output
2
<class 'list'>
python
<class 'dict'>
{1, 2}
2

### chapter 2 : lists in detail
##### contents of list include :
1.sort the values by ascending or descending order
2.find the values in the lists and list length sizes
3.operations on list level insert delete update on the items of the lists
4.add and remove another sub lists or lists directly to the current list 

important methods in lists 
 sort -- sort(),sorted(list)
 append(),insert(),extend(),remove(),pop()
 len(),indexing,slicing count()
 slicing,copying shallow vs deep copy
##### example program 
```sh
l= [1,2,2,3,4,1,22,3,44,]
string_list =["aa","bb","aa","cc","aa","dde"]
#sorted doesnt change the list its a temporary manipulator of list elements
new_l=sorted(l)
print(new_l)
# list.sort method actually changes the list values after sorting 
l.sort()
print("my actual list after sorting",l  )

# checking item existing in list using IN operator  
print("aa" in string_list )

# searching the index of required element 
print(string_list.index("dde"))

#finding the length
print("length of my string list is ",len(string_list))

# finding the minnimun and maximum elements in the list

print("minmim value :",min(l))
print("maximum value :",max(l))

# to chech the prededined methods in the list 
print(dir(list))



```
#####  output
[1, 1, 2, 2, 3, 3, 4, 22, 44]
my actual list after sorting [1, 1, 2, 2, 3, 3, 4, 22, 44]
True
5
length of my string list is  6
minmim value : 1
maximum value : 44
methods on list class are :
['__add__', '__class__', '__contains__', '__delattr__', '__delitem__', '__dir__', '__doc__', '__eq__', '__format__', '__ge__', '__getattribute__', '__getitem__', '__gt__', '__hash__', '__iadd__', '__imul__', '__init__', '__init_subclass__', '__iter__', '__le__', '__len__', '__lt__', '__mul__', '__ne__', '__new__', '__reduce__', '__reduce_ex__', '__repr__', '__reversed__', '__rmul__', '__setattr__', '__setitem__', '__sizeof__', '__str__', '__subclasshook__', 'append', 'clear', 'copy', 'count', 'extend', 'index', 'insert', 'pop', 'remove', 'reverse', 'sort']


