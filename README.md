# week-2-lab-project-2
Cis-30 week 2 lab
daily_penguin_ration = 7 #in kg
daily_seal_ration = 9 #in kg
daily_polar_bear_ration = 11 #in kg
days_in_month = 30
num_of_penguins = int(input("Enter the number of penguins: "))
num_of_seals = int(input("Enter the number of seals: "))
num_of_polar_bears = int(input("Enter the number of polar bears: "))
monthly_food_consumption_penguins = round(num_of_penguins * daily_penguin_ration * days_in_month)
monthly_food_consumption_seals = round(num_of_seals * daily_seal_ration * days_in_month)
monthly_food_consumption_polar_bears = round(num_of_polar_bears * daily_polar_bear_ration * days_in_month)
print(f"The food consumed by penguins is {monthly_food_consumption_penguins} kg")
print(f"The food consumed by seals is {monthly_food_consumption_seals} kg")
print(f"The food consumed by polar bears is {monthly_food_consumption_polar_bears} kg")
