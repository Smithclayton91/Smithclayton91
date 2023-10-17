- 👋 Hi, I’m @Smithclayton91
- 👀 I’m interested in class Airplane: def __init__(self, make, model, capacity, fuel_capacity): self.make = make self.model = model self.capacity = capacity self.fuel_capacity = fuel_capacity self.fuel_level = 0 def refuel(self, gallons): if self.fuel_level + gallons <= self.fuel_capacity: self.fuel_level += gallons print(f"Refueled {gallons} gallons of fuel.") else: print("Cannot add that much fuel, it exceeds the capacity.") def take_off(self): if self.fuel_level >= 10: self.fuel_level -= 10 print("Taking off...") else: print("Not enough fuel to take off. Please refuel.") def land(self): print("Landing.") self.fuel_level = 0 # Create an instance of an airplane my_airplane = Airplane("Boeing", "747", 416, 50000) # Example usage my_airplane.refuel(2000) my_airplane.take_off() my_airplane.land()
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Smithclayton91/Smithclayton91 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
