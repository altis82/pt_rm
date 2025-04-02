# Basic
## Type casting
## Exception
## List
Append(x) 

Insert(I,x) 

Remove(x) remove first item 

Pop([I]) 

Clear() 

Index(x,start, end) 

my_list = ['apple', 'banana', 'cherry', 'apple', 'banana']  

index = my_list.index('apple', 1, 4) print(index) # Output: 3 

Count 

Sort 

Reverse 

Copy 
## Set 
- Define a set `A={1,2} `

Union `A={1,2,3} B={2,3}` 

`print(A|B) `

`print(A.Union(B)) `

- Intersection  

`print(A-B) `

`print(A.Intersection(B)) `

- Difference  

A.difference(B) ==>{1} 

A-B 

Subset A.issubset(B) ==> true 

Symmetric diff  A={1,2,3,4} B ={2,3,5} 

A.symmetric_difference(B) ==>{4,5} 

Superset A={1,2,3} B={1,2} A.issuperset(B) ==>true 

Pass an array to a set 

S = set([1, 10, 100]) 

 