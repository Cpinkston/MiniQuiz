##Quetion 1
<pre><code>class prime_generator():
	def __init__(self):
		self.n = 1

	def next(self):
		prime = False
		self.n += 1
		while prime == False:
			for x in range(2, self.n-1):
				if self.n % x == 0:
					self.n += 1
					continue
			prime = True 
		return self.n
</code> </pre>

##Quetion 2

<pre><code>class Animal(Object):
	population = 0

	def __init__(self, age = 0):
		self.age = age
		Animal.population += 1

	def eat():
		print "The animal ate"

class Dog(Animal):
	def __init__(self, age = 0, name):
		Animal.__init__(self, age):
		self.name = name

	def walk():
		print self.name " walked forward."

	def speak():
		pring "Bark!"

class Snake(Animal):
	def __init__(self, age = 0)
		Animal.__init__(self, age)

	def eat():
		print "The snake unhinged its jaw."

	def hiss():
		print "Ssssss!"
</code> </pre>

