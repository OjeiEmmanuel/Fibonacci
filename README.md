# Fibonacci
Using a for loop to generate first n Fibonacci sequence
Init_list = [0,1,1]
#iterating the Init_list
for i in range(n):
    Init_list.append((Init_list[-2] + Init_list[-1]))
Print(Init_list)
