# LA-15

class Dog:
    def __init__(self, name):
        self.name = name

    def speak(self):
        print("Bark!")
            
class Cat:
    def __init__(self, name):
        self.name = name
        
    def speak(self):
        print("Meow!")
        
class Bird:
    def __init__(self, name):
        self.name = name
        
    def speak(self):
            print("Chirp")
            
class Fish:
    def __init__(self, name):
        self.name = name
        
    def speak(self):
            print("...")
            
dog = Dog("Siberian Husky")
cat = Cat("Birman")
bird = Bird("Gambel’s Quail")
fish = Fish("Coral Trout")

for animal in [dog, cat, bird, fish]:
    animal.speak()
    

    
