# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the file in read mode and handle it in test mode
### Step 2: 
 Read the text using read() function.
### Step 3: 
Split the text using space separator.We assume that words in a sentance are separted by a space character
### Step 4:  
The length of the split list should equal the numbers of words in the test file.
### Step 5: 
You can refine the count by cleaning the string prior to splitting or validating the words after splitting.
### Step 6: 
End the program.
## PROGRAM:
~~~
Developed by : A.Mandhakini
Registered number: 23010115

def wordcount(filename):
    count=0
    with open(filename,"r") as f:
        for data in f:
            words=data.split()
            for word in words:
                count+=1
    print("Total number of words:",count)
filename=input("Enter Filename:")
wordcount(filename)
~~~

### OUTPUT:
![image](https://github.com/MandhakiniA/Word-count/assets/150005194/b417a07a-5ada-4a3b-8e17-0b9e0765b63c)
![image](https://github.com/MandhakiniA/Word-count/assets/150005194/86643c5b-3692-4dcd-bb61-de4b8b186bba)





## RESULT:
Thus the program is written to find the word count from a text.
