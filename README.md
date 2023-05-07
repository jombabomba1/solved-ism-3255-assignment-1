Download Link: https://assignmentchef.com/product/solved-ism-3255-assignment-1
<br>
5/5 - (3 votes)

Write an application that grades a multiple choice test with 10 questions taken by 4 students. The application finds each student’s grade based on that test, and then displays: a table listing students’ numbers and theirs grades out of 10 (the number of correct answers).The students’ numbers, their answers to the questions, and the answer key for all questions are as given below.Student’s Number                      Student’s Answers to the Questions1                   A B A C C D E E A D2                   D B A B C A E E A D3                   E D D A C B E E A D4                   C B A E D C E E A D



Key                 D B D C C D A E A D

Sample Input1-      Each student’s number and their answers are presented in a string variable in the following format:“NXXXXXXXXXX”

Note that the first character represents a student number. The student’s first answer starts at the second character of the string (the 10 answers by the same student are NOT separated by spaces). The length of the each string is 11 characters. So students’ information can be coded as follows:

string s1=”1ABACCDEEAD”;string s2=”2DBABCAEEAD”;string s3=”3EDDACBEEAD”;string s4=”4CBAEDCEEAD”;

2-      The answer keys are presented in a string variable in the following format:string keys=”DBDCCDAEAD”;

HINT: You can copy this piece at the beginning of your Main method:string s1=  “1ABACCDEEAD”;string s2=  “2DBABCAEEAD”;string s3=  “3EDDACBEEAD”;string s4=  “4CBAEDCEEAD”;

string keys= “DBDCCDAEAD”;

Console.WriteLine (“Students Number    Student Grade”);

Sample Output