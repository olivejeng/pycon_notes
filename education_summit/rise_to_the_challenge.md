## Practice problem example -
Ask a user to imput their name, and turn their name from a string into ASCII.
### Input:
Jorge

###Output:
J ASCII value is 74
o ASCII value is 111
r ASCII value is 114
g ASCII value is 103:

###Code:
`x = input("What is your name?: ")
for i in x[:4]:
	print(f "{i} ASCII value is {ord(i)}")`
