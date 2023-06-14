# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: Import sys module

### Step 2: Open the file with sys.argv[1]
 
### Step 3: Use the for loop to select the content in file

### Step 4:  Use split function to to separate the file content into words or strings

### Step 5: Count the length of the words using len

### Step 6: Print the number of words

## PROGRAM:
    #program to command-line-arguments-to-count-word
    #Developed by: Dhiyaneshwar P
    #RegisterNumber: 212222110009
    import sys
    fp=open(sys.argv[1], 'r')
    count=0
    for line in fp:
        list1=line.split()
        count+=len(list1)
    print("No of words in a file",count)

### OUTPUT:

![244876486-3886a6a5-6f39-413c-a3af-f88abe645463](https://github.com/Dhiyanesh24/command-line-arguments-to-count-word/assets/118362288/39aa11a4-0ab2-4164-8b9f-4325542ccb61)
![244876508-9f7c0311-98af-49e7-bda7-b806a383354a](https://github.com/Dhiyanesh24/command-line-arguments-to-count-word/assets/118362288/c3432472-4717-435f-9e80-affc8add1f4f)
![244876516-5f3d572c-e558-4930-89a9-99d4653e9330](https://github.com/Dhiyanesh24/command-line-arguments-to-count-word/assets/118362288/ba8f25da-b9d4-4928-8b78-44a68ae3a49d)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
