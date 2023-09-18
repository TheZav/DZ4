class Studnet():
    def __init__(self,name,age,height,mass,eyecolor,haircolor,favcolor,favsubject,grade,hobby):
      self.name = name
      self.age = age
      self.height = height
      self.weight = mass
      self.eyecolor = eyecolor
      self.haircolor = haircolor
      self.favcolor = favcolor
      self.favsubject = favsubject
      self.grade = grade
      self.hobby = hobby
      print(f"Your name is {self.name},your age is {self.age} years, your height is {self.height} centimeters, your weight is {self.weight} kilograms, you have {self.eyecolor} colored eyes, you have {self.haircolor} colored, you quite like color {self.favcolor} and studying {self.favsubject}, you are in {self.grade} grade and you like {self.hobby}. You are a unique human being.")
n = input("Your name  ")
a = input("Your age  ")
h = input("Your height  ")
w = input("Your weight  ")
ec = input("Your eye color  ")
hc = input("Your hair color  ")
fc = input("Your favourite color  ")
fs = input("Your favourite subject  ")
g = input("Your grade  ")
ho = input("Your hobby  ")
Studnet(n,a,h,w,ec,hc,fc,fs,g,ho)
