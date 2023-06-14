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
#Developed by:SHABREENA VINCENT
#Reg no:212222230141

with open('f1.txt','r')as f1:
    with open('f2.txt','a')as f2:
        for line in f1:
            f2.write(line)
      
```
### OUTPUT:

![output](https://github.com/shabreenavincent/copy-file/assets/119475721/6c45d858-6105-4639-93b9-26ff872b834e)

### FILE1:

![file1](https://github.com/shabreenavincent/copy-file/assets/119475721/f73c91b1-df2b-43bc-95b8-441abe4f24ef)
### FILE2:

![file2](https://github.com/shabreenavincent/copy-file/assets/119475721/7693870c-8973-4d00-b5e1-c8aa6e145e1c)

### FILE 1 copied to FILE 2:

![file 1 file 2 copied](https://github.com/shabreenavincent/copy-file/assets/119475721/ee3e4cae-7a64-4332-9c13-16fc21b7ab93)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
