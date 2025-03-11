# new-rep

atr array
class student:
	def __init__(self, name,age):
		self.name = name
		self.age = age
s1 = student("abc",20)
print(getattr(s1,"name"))
print(getattr(s1,"age"))
print(getattr(s1,"grade","hdfkjlf"))


#method 
class Person:
	def __init__(self,name,age):
		self.name = name
		self.age = age
	def greet(self):
		print(f"hello, my name is {self.name} and iam {self.age} years old")
person1 = Person("akhil",25)
person1.greet()

