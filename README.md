# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Get the file name and location from the user.
### Step 2: 
Give a new file name to create a copy of a file content. 
### Step 3: 
Read the file and close the file.
### Step 4:  
Now write the content in the new file.
### Step 5: 
When done print "File copied successfully".
### Step 6: 
End of the program.

## PROGRAM:
```
'''Program For Copying The Contents:
Developed by: ARAVINDHNATH T R
RegisterNumber: 22009024 '''

print("Enter the Name of Source File: ")
sFile = input()
print("Enter the Name of Target File: ")
tFile = input()
fileHandle = open(sFile, "r")
texts = fileHandle.readlines()
fileHandle.close()

fileHandle = open(tFile, "w")
for s in texts:
    fileHandle.write(s)
fileHandle.close()

print("\nFile Copied Successfully!")
```
## OUTPUT:
![Copy file](https://user-images.githubusercontent.com/118790841/214720994-b1ea0759-137f-485b-9c0f-65b1706d8b84.jpg)

![Copy file2](https://user-images.githubusercontent.com/118790841/214721010-2104b3cc-495d-44b3-9bdd-023be40d7a51.jpg)

![Copy file3](https://user-images.githubusercontent.com/118790841/214721024-9a1f2363-6fc3-40f5-9d9b-9f7c29f0b321.jpg)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
