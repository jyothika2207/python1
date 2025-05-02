#sample program for sampling
a=int(input("enter the number"))
b=int(input("enter the number"))
a=a+b
b=a-b
a=a-b
print("after swapping:")
print("a:",a)
print("b:",b)


#converting into a set 
nums=[1,2,3]
unique=set(nums)
print(unique)

#program for subsets
a={1,2}
b={1,2,3,4,5}
print(a.issubset(b))
print(b.issubset(a))
