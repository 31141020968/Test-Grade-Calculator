# Test-Grade-Calculator
-Introduce: Project help to build function analyze and caculate the grade of each class through student's answers file


-Condition:
Before you continue, ensure you meet the following requirements:
* You have installed the Python. 
* You have installed of numpy and pandas library.
* You have a basic understanding of numpy and pandas library.
* 

-Install:

*Install Python: Download: https://www.python.org/downloads/

*Install library:

Numpy:https://numpy.org/install/

Pandas:https://pandas.pydata.org/docs/getting_started/install.html


-Using:

+Task1: open file

Use function open_file()

Ex: file1 = open_file()

Input: user enter the name of file (ex: class1) to open the file. 

Output: if the file exists, notify successfull else it does not exist, notify unsucessful


+Task2: analyze file about format such as: enough 25 answers and 1 ID, correct ID format (start with "N" and include 8 digits) 

Use function open_file() at task 1 and use function analyze_file(file) - file is a parameter at task 1

Ex: 

file1 = open_file()

analyze_file(file1)

Output: the number lines of file is valid and unvalid and list detail the unvalid lines with its error


+Task 3: calculate the grade of each student (only the valid line) with answer_key and statistic mean, max, min, median of each class 

Use function open_file() at task 1 and use function calculate_score(file)

Ex:

file1 = open_file()

calculate_score(file1)

output: List ID, score of each student, statistic mean, max, min, median of each class 


+Task4: save list at task 3 into file with the name base on name file original (ex: "class1" -> save to “class1_grades.txt”). 

Use function open_file() at task 1 and use function save_result(file,df_result) - file is a paramester at task 1, df_result is a data frame score at task3

Ex: 

file1 = open_file()

save_result(file1,calculate_score(file1))



Thank you

