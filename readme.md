[Complete on Replit](https://replit.com/@whs-spring-2023/Midterm-1)

1. Output your first and last name

```
print(_)
```
Example Output:
```
First Last
```

</br>
2. Write a function that takes your first initial, last name and grade as arguments and returns a formatted sentence. 

- The sentence should be formatted as follows: "Last Name, First Initial, Grade" ~> Whitby, D. 12

- Output the resulting sentence

```
def name_and_grade(first_initial, _, _):

  # Format sentence below
  sentence =  ...

  # Don't forget to return the formatted sentence

print(name_and_grade("D", "Whitby", 12))
```

</br>
3. Write a function that takes a number (n) as an input and returns the numbers 1 through n.

```
def consecutive_numbers(n):

  number_list = []

  for i in range(1, _):
    factor_list.append(i)

  return number_list

print(_)
```
</br>
4. Write a function that takes a number (n) as an input and returns all factors of n.

```
def factors(n):

  factor_list = ...

  for i in range(1, n):
    
    if n % i == _:
      ...
      

  return factor_list

print(_)
```

</br>
5. Write a function that outputs your grade on this midterm.


print("Jesse Sanchez")



def name_and_grade( Last_Name ,first_initial , Grade):

  sentence = "My last name is {Last_Name}, my first initial is {first_initial} , and my grade is {Grade}".format(Last_Name = "Sanchez" , first_initial = "J", Grade = str(9) )
  return sentence
  
  
  
 def consecutive_numbers(n):

  number_list = []

  for i in range(1, n):
    number_list.append(i)

  return number_list

print(number_list)


def factors(n):

  factor_list = [1,2,3,4,5]

  for i in range(1, n):
    
    if n % i == 0:
    factor_list.append(i)
      

  return factor_list

print(8)


print(100)
