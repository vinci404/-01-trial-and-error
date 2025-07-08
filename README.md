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
	print("Status: Junior student")
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

# this will ask for student's name, age, grade, and GWA then it will print the name, age, grade and status (graduating student if it is grade 12), GWA (with "graduating with honors", i don't know how to put the <90 to tell that "graduating with honors" and those below 90 should execute "congratulations" so yeah, and then it will print the name with the message and ask for student's opposite number because I'm trying to put what I learned for arithmetic operators.
# this is my first ever try so yeah it still have some errors but it runs in Pydroid 3 I'm sooooooooo happy, so this is the feeling when your code runs after so many errors huh it's so fulfilling, i felt like NASA or Google should hire me hahahahaha kidding


# okay so i tried to fix some things and here's the updated one

# ask for students name, grade, and gwa
print("Greetings student!")
print("Student 01 profile")
name1 = input("Enter your name:" )
age1 = input("Enter your age:" )
grade1 = int(input("Enter your grade:" ))
gwa1 = float(input("Enter your gwa:" ))
print("Name:", name1)
print("Age:", age1 + " years old")
print("Grade:", grade1)
if grade1 > 12:
	print("Status: Graduating student")
else:
	print("Status: Junior student")
print("GWA:", gwa1)
if gwa1 >= 90:
    print("Graduating with honor")
else:
    print("Congratulations")
name1_1 = [(name1)]
for name1_1 in name1_1:
	print("HI!", name1 + ", AIM HIGH, FLY HIGH, AND BE ON TOP!")
student1_number = input("Enter your opposite student no.:" )
all_students = 100
print("Student:", all_students - int(student1_number))
