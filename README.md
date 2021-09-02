#Student Portfolio

name = str(input("Name of the Student: "))
Clas = int(input("Standard of the Student: "))
division = str(input("Division: "))
roll = int(input("Roll number: "))
print("\n")
print("-" * 50)

print(name + " is studying in " + str(Clas) + "-" + division)
print("-" * 50)
print("\n")

print("Write the name of all 5 subjects? ")

sub1 = input("Subject-1: ")
sub2 = input("Subject-2: ")
sub3 = input("Subject-3: ")
sub4 = input("Subject-4: ")
sub5 = input("Subject-5: ")
print("\n")
print("How much marks " + name + " get in all 5 subjects?")

s1 = (int(input(sub1 + ":")))
s2 = (int(input(sub2 + ":")))
s3 = (int(input(sub3 + ":")))
s4 = (int(input(sub4 + ":")))
s5 = (int(input(sub5 + ":")))
print("\n")
print("-" * 50)

total = int( s1 + s2 + s3 + s4 + s5)
print("Total Marks = " + str(total))

perct = float(total*100/500)

print("Percentage: " + str(perct))

print("-" * 50)
print("\n")
print("Name: " + name)
print("Standard: " + str(Clas) + "-" + division)
print("Roll Number: " + str(roll))

print("\n")
print(name + " got " + str(perct) + "%" + " in " + str(Clas) + "-" + division)
print("\n")
print("*" * 5 + "THANK YOU" + "*" * 5)
