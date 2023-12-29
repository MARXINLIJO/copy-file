# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Use open function to open a file in which we want to copy from and access it in read mode.
### Step 2: 
 Read the file and store in a variable
### Step 3: 
Now create a new file in which we want to paste the content using write access mode.
### Step 4:  
Use write function to copy the read file that has been stored in the variable
### Step 5: 
The content in the original file will be copied in the new file.
### Step 6: 
End the program
## PROGRAM:
```
with open('original.txt','r') as fp:
    msg1=fp.read()
with open('copy.txt','a')as fp1:
    fp1.write(msg1)
```
### OUTPUT:
![image](https://github.com/MARXINLIJO/copy-file/assets/145742540/3cb4a582-7f1d-49ab-8329-d60f720f447f)
![image](https://github.com/MARXINLIJO/copy-file/assets/145742540/cd894e66-0303-4c00-bc10-cda476d12ae7)
![image](https://github.com/MARXINLIJO/copy-file/assets/145742540/214ce2a0-c286-4c65-a8ac-f4e9735e498d)




## RESULT:
Thus the program is written to copy the contents from one file to another file.
