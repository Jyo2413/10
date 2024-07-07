
import numpy
n = int(input("Enter number of elements to insert into the dictionary: "))
my_dict= {}
for x in range(n):
new_key =input('Enter new key: ')
 new_value = input('Enter new value: ')
 my_dict[new_key] = new_value
lst = []
n = int(input("Enter number of elements to insert into the list : "))
for i in range(0, n):
 ele = int(input('Enter an item: '))
 lst.append(ele)
lst_arr = numpy.array(lst)
dict_array = numpy.array(list(my_dict.items()))
print ("List: ", lst)
print ("List Array: ", lst_arr)
print ("Dictionary: ", my_dict)
print ("Dictionary Array: ", dict_array)
