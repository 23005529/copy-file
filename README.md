# copy-file
### Name : Aliya Sheema
### Register Number : 23005529
### Department : AIDS
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a text file with some content in it.
### Step 2: 
Open the created text file. 
### Step 3: 
Create another empty text file.
### Step 4:  
Copy the content of text file to empty file using write function. 

## PROGRAM:
### Program for copying the contents from one file to another file
### Developed by: Aliya Sheema
### Register Number: 23005529
```
with open("shyam.txt",'r') as file1:
    msg=file1.read()
with open("shyamnew.txt",'w') as file2:
    file2.write(msg)
 ```   
### OUTPUT:
![Screenshot 2024-01-02 211736](https://github.com/23005529/copy-file/assets/139842207/4cafaa4f-5f44-453c-a33b-71638cf6427f)
![Screenshot 2024-01-02 211758](https://github.com/23005529/copy-file/assets/139842207/a38704c7-6444-47dc-b699-31427a475b92)
![Screenshot 2024-01-02 211815](https://github.com/23005529/copy-file/assets/139842207/8e22cf3f-771f-4cfb-a826-800a8998e89d)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
