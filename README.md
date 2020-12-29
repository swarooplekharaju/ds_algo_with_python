#  PROBLEM SOLVING WITH PYTHON 3 
CONTENTS
 PART 1 :-> PYTHON PROGRAMMING BASICS 
         1.INTRODUCTION TO COLLECTIONS IN PYTHON 
         2.LISTS EXPLAINED IN DETAIL
PART 2 : ALGORITHAMS IN PYTHON 


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
