# Count-Characters-Words-and-Lines-in-a-File
file = open('a.txt', 'r')
char = 0
words = 0
lines = 0
for line in file:
    lines += 1
    words += len(line.split())
    char += len(line)
file.close()
print("The no. of chars is", char)
print("The no. of words is", words)
print("The no. of lines is", lines)

OUTPUT:
Hello world
Python is easy
The no. of chars is 26
The no. of words is 5
The no. of lines is 2
