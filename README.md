# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the required file by using the function "with" in read mode.
### Step 2: 
 Open the another required file by using the function "with" in append mode to append.
### Step 3: 
Use for loop in file1.
### Step 4:  
Use write function.
### Step 5: 
To write the file 1 content in file 2.
### Step 6: 
End the program.
## PROGRAM:
```

program developed by: shabreena vincent
registration number:212222230141
with open("file.txt") as fp:
    with open("fire2.txt","w") as fp1:
        line= fp.read()
        fp1.write(line)
      
```
### OUTPUT:

![f1](https://github.com/shabreenavincent/copy-file/assets/119475721/73e2d9fa-00f9-4834-a2b4-9da294c6993c)

![f2](https://github.com/shabreenavincent/copy-file/assets/119475721/0fe07f7f-4855-48d8-a6bd-9f89e69f1c87)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
