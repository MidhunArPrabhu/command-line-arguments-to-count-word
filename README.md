# COMMAND-LINE-ARGUMENTS-TO-COUNT-WORD 

## AIM:

To write a python program for getting the word count from the contents of a file using command line arguments.

## EQUIPEMENT'S REQUIRED :

- PC
- Anaconda - Python 3.7

## ALGORITHM :

### STEP 1 :

Get the file name using command arguments

### STEP 2 :

Now read the content in the file

### STEP 3 :

use split()

### STEP 4 :

Now read the no.of words in file

### STEP 5 :

Print number of words present in given file

### STEP 6 :

End of the program


## PROGRAM :

```python
Developed by: MIDHUN AZHAHU RAJA P
RegisterNumber: 22008311

import sys
count = {}
with open(sys.argv[1], 'r') as f:
    for line in f:
        for word in line.split():
            if word not in count:
                count[word] = 1
            else:
                count[word] += 1
print(count)
f.close()
```
### OUTPUT :

![output (1)](https://user-images.githubusercontent.com/118054670/213933892-ca3685ef-8ca8-46fe-9c7c-149433d166e1.png)


## RESULT :

Thus the program is written to find the word count from the contents of a file using command line arguments.
