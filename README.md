# -01-trial-and-error
Putting some stuff that I learned from 1hr vids.
``` python

# july 9

# ask for students name, grade, and gwa
print("Greetings student!")
print("Student 01 profile")
name1 = input("Enter your name:" )
age1 = input("Enter your age:" )
grade1 = input("Enter your grade:" )
gwa1 = input("Enter your gwa:" )
print("Name:", name1)
print("Age:", age1 + " years old")
print("Grade:", grade1)
if grade1:
	print("Status: Graduating student")
else:
	pring("Status: Junior student")
print("GWA:", gwa1)
if gwa1:
	print("Graduating with honor")
else:
	print("Congratulations")
name1_1 = [(name1)]
for name1_1 in name1_1:
	print("HI!", name1 + ", AIM HIGH, FLY HIGH, AND BE ON TOP!")
student1_number = input("Enter your opposite student no.:" )
all_students = 100
print("Student:", all_students - int(student1_number))
