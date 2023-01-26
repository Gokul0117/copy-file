# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open Jupyterlab and a plain text file and save the file with .txt extension

### Step 2: 
Enter some words in file.txt file.
 
### Step 3: 
Create python notebook.

### Step 4:  
Enter the code with file name as excatly given in .txt extension.


### Step 5: 
Run the code ,it will copy from file to file2
### Step 6: 
Open the file2.txt it will copy the input and display.


## PROGRAM:
```
Developed by: Gokul J
Register number: 22009062

with open('a1.txt','r')as firstfile:
    with open('a2.txt','a')as secondfile:
        for line in firstfile:
            secondfile.write(line)
```            
            

### OUTPUT:
![Screenshot from 2023-01-26 17-29-01](https://user-images.githubusercontent.com/121165938/214830029-2fe7e517-ac57-4819-9899-6f4fa9ab8834.png)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
