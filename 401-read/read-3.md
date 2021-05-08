# Reading and Writing Files in Python

The file :
 a file is a contiguous set of bytes used to store data. This data is organized in a specific format

Files main parts :
Header: metadata about the contents of the file 
Data: contents of the
End of file (EOF): special character that indicates the end of the file

Folder Path: the file folder location on the file system
Extension: the end of the file path pre-pended with a period (.) used to indicate the file type

To get file path you need to go through the path folder and then the next folder, even arriving at the  file.

double-dot (..) to move one directory up.

Opening a File in Python :
`file = open('dog_breeds.txt')`

It is important to close all file that opened before :

two ways to ensure that a files is closed properly :
1- try-finally 

`reader = open('dog_breeds.txt')`
`try:`
    `# Further file processing goes here`
`finally:`
    `reader.close()`

2- with statement :
`with open('dog_breeds.txt') as reader:`
    `# Further file processing goes here`
The with statement automatically takes care of closing the file once it leaves the with block

**Open modes :**
- `r` :	Open for reading (default)
- `w` :	Open for writing, truncating (overwriting) the file first
- `rb`  or `wb`	: Open in binary mode (read/write using byte data)

`open(file path', 'Open mode')`
`open(‘file path') # reading mode by default`

three different categories of file objects:
- Text files
- Buffered binary files
- Raw binary files

.read(size=1) : Reads from the file based on the number of size bytes 
.readline() returns a list where each element in the list represents a line in the file

`with open('dog_breeds.txt', 'r') as reader:`
 `print(reader.readline(5)) `

`with open('dog_breeds.txt', 'r') as reader:`
`# Read and print the entire file line by line`
`for line in reader:`
`print(line, end='')`

The end='' is to prevent Python from adding an additional newline to the text that is being printed

.readlines() : reads the remaining lines from the file object and returns them as a list.

`f = open('dog_breeds.txt')`
`list(f)`

writing   methods : 
.write(string) : This writes the string to the file.

.writelines(seq)	This writes the sequence to the file. No line endings are appended to each sequence item. It’s up to you to add the appropriate line ending(s).
Example : 

`with open('dog_breeds_reversed.txt', 'w') as writer:`
    `for breed in reversed(dog_breeds):`
        `writer.write(breed)`

 to work with files using byte strings. This is done by adding the 'b' character to the mode argument. 

`with open('dog_breeds.txt', 'rb') as reader:`
    `print(reader.readline())`

to append to a file or start writing at the end of an already populated file , use the 'a' character for the mode argument:

`with open('dog_breeds.txt', 'a') as a_writer:`
    `a_writer.write('\n String')`

The new text will be added to the end of the file

**Working With Two Files at the Same Time**

`d_path = 'dog_breeds.txt' d_r_path = 'dog_breeds_reversed.txt' with `
`(d_path, 'r') as reader, `
`(d_r_path, 'w') as writer:`
 `dog_breeds = reader.readlines() writer.writelines((dog_breeds))`

**Working With Two Files at the Same Time**

`d_path = 'dog_breeds.txt' d_r_path = 'dog_breeds_reversed.txt' with `
`(d_path, 'r') as reader,` 
`(d_r_path, 'w') as writer: dog_breeds = reader.readlines() writer.writelines((dog_breeds))` 


# Python Exceptions

Syntax errors occur when the parser detects an incorrect statement

exception error : occurs whenever syntactically correct Python code results in an error , for example : 0/0

Raising an Exception
`x = 10 if x > 5: raise Exception('x should not exceed 5. The value of x was: {}'.format(x)) `

occurs  on special cases
`assert (<condition>), “Error message" `

The try and except Block: Handling Exceptions :
To prevent the code from stopping if an error happened and show  an  error message and the rest of the code continues to run

`try:` 
 `function() `
`except:`

to see exactly what went wrong, you would need to catch the error that the function threw.
`try:`
  `<code>`
`except AssertionError as error: `
  `print(error) `

The else Clause
In Python, using the else statement, you can instruct a program to execute a certain block of code only in the absence of exceptions.

If the program did not run into any exceptions, the else clause will execute

`try: linux_interaction() except AssertionError as error:` 
`print(error)`
 `else:` 
`('Executing the else clause.') `

Finally : The code inside it is executed whether an error occurs or not
`try:`
  `<code>`
`except AssertionError as error:`
 `print(error)`
`else:`
 `print ('else')`
`finally:`
 `print(‘anyway’)`
