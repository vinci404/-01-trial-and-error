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




# look what i just didddd, i'm sooooo happy
# exercise: create something that asked for student's status and print some motivational message
print("Greetings academic weapon!")
print("Keep on studying, learning, and growing \n")
course = "aim high, fly high, and be on top!"
print(course.upper())
name = input("Name:" )
grade = int(input("Grade:" ))
print("Name:", name)
if grade == 12:
	print("Senior high: gradWAITING")
elif grade == 11:
	print("Senior high")
elif grade == 10:
	print("Junior high: gradWAITING")
elif grade > 6:
	print("Junior high")
else:
	print("Elementary")
section = input("Section:" )
print("Section:", section)
gwa = float(input("GWA:" ))
print("GWA:", gwa)
if gwa >= 98:
	print("Continue to aim, to fly, and you will reach the top. We are rooting for your success kid, our brightest star!")
elif gwa >= 97:
	print("Spread you wings, go fly for your dreams, go further and higher. We are rooting for your success kid, our star")
elif gwa >= 94:
	print("Aim for the highest, fly and be the brightest. We are rooting for your success kid, our future star")
elif gwa >= 90:
	print("Keep you heart at blaze, use the spark to fly and aim straight for the highest. We are rooting for your success kid, our wannabe star")
elif gwa >= 85:
	print("Go explore the world. Be the light if you can't fly, be the arrow if you can't aim, be what others cannot. We are rooting for your success kid, our shifting star")
else:
	print("Life doesn't end when you don't get what you wanted. Keep on trying, keep on believing, keep on breathing. You still matter. Your existence matter and we are thankful for that. We are rooting for you success kid, our burning star")

print("_____________________ \n")

course = "keep on aiming, flying, and sailing. your journey are just started, create a life full of wanders and imperfections."
print(course.upper())
