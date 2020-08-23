# My-First-code-Class-and-Object-

print("VEHICLES")
print('\n')

class Vehicle:
    def __init__(self,car,bike):
        self.car = car
        self.bike = bike
    
    def show_vehicle_detail(self):
        print("Number of Cars = ", self.car)
        print("Number of Bikes = ",self.bike)
        print("We are vehicles")

v1 = Vehicle(3,2)
v1.show_vehicle_detail()

print('\n')
print("CARS")
print('\n')

class Car(Vehicle):
    def __init__(self, brand):
        self.brand = brand

    def show_car_detail(self):
        print("My Brand is ", self.brand)

c1 = Car('BMW')
c1.show_car_detail()
c2 = Car("Ferrari")
c2.show_car_detail()
c3 = Car("Lamborgini")
c3.show_car_detail()

print('\n')
print("BMW")
print('\n')

class Bmw(Car):
    def __init__(self,milage,price):
        self.milage = milage
        self.price = price

    def show_bmw(self):
        print("My Milage is = ", self.milage)
        print("My Price is = ",self.price)

b1 = Bmw(563,1000000)
b1.show_bmw()

print('\n')
print("FERRARI")
print('\n')

class Ferrari(Car):
    def __init__(self,milage,price):
        self.milage = milage
        self.price = price

    def show_ferrari(self):
        print("My Milage is = ", self.milage)
        print("My Price is = ",self.price)

f1 = Ferrari(593,3000000)
f1.show_ferrari()

print('\n')
print("LAMBORGINI")
print('\n')


class Lamborgini(Car):
    def __init__(self,milage,price):
        self.milage = milage
        self.price = price

    def show_lamborgini(self):
        print("My Milage is = ", self.milage)
        print("My Price is = ",self.price)

l1 = Lamborgini(578,2000000)
l1.show_lamborgini()

print('\n')
print("BIKES")
print('\n')

class Bike(Vehicle):
    def __init__(self, brand):
        self.brand = brand

    def show_bike_detail(self):
        print("My Brand is = ", self.brand)

m1 = Bike('Glamour')
m1.show_bike_detail()
m2 = Bike("Pulsar")
m2.show_bike_detail()

print('\n')
print("GLAMOUR")
print('\n')

class Glamour(Bike):
    def __init__(self,milage,price):
        self.milage = milage
        self.price = price

    def show_glamour(self):
        print("My Milage is = ", self.milage)
        print("My Price is = ",self.price)

g1 = Glamour(150,67000)
g1.show_glamour()

print('\n')
print("PULSAR")
print('\n')

class Pulsar(Bike):
    def __init__(self,milage,price):
        self.milage = milage
        self.price = price

    def show_pulsar(self):
        print("My Milage is = ", self.milage)
        print("My Price is = ",self.price)

p1 = Pulsar(150,75000)
p1.show_pulsar()
