# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
To write a python program for getting the word count from a text file.

### Step 2:
Open the required file by using the function "with".

### Step 3: 
Then use the for loop to assign the i value in the file.

### Step 4:
Using split function to spilt the words.

### Step 5:
Finding the given length of the words by using len() fuction.

### Step 6:
Calling the function and [rinting the number of words.

## PROGRAM:
#Program to count number of words in the text file

#Developed by:Alagu nachiyar

#Register no:22002084
```
num_word=0
with open('nachi.txt') as f6:
    for i in f6:
        word=i.split()
        num_word+=len(word)
print("Number of words:{}".format(num_word))
```

### OUTPUT:
![count wordex](https://user-images.githubusercontent.com/113497340/192227792-ff6a744e-c274-47f8-b03b-54150771cf56.png)


![txtfile](https://user-images.githubusercontent.com/113497340/192227844-eff7c233-9cfc-45b3-bd3b-ecf3fad4fe73.png)





## RESULT:
Thus the program is written to find the word count from a text.
