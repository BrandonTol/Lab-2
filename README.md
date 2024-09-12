1)
# Displaying the students information
print("Name: Cameron Calero")
print("Address: 2045 Heliport Loop, Riverfolk, IN 43286")
print("Telephone: 812-555-1212")
print("College Major: Undeclared")

# ----------------------------------------

2)
# Get the projected total sales
total_sales = float(input("Enter the projected total sales: "))

# Calculate profit
profit = total_sales * 0.23

# Display the profit
print("The projected profit is:", profit)

# ----------------------------------------

3)
# Define the conversion factor: 1 acre = 43,560 square feet
square_feet_per_acre = 43560

# Get the total square feet
total_square_feet = float(input("Enter the total square feet in the tract of land: "))

# Calculate the number of acres
acres = total_square_feet / square_feet_per_acre

# Display the result
print("The number of acres is:", acres)

# ----------------------------------------

4)
# Define the sales tax rate
sales_tax_rate = 0.07

# Ask for the prices of five items
price1 = float(input("Enter the price of item 1: "))
price2 = float(input("Enter the price of item 2: "))
price3 = float(input("Enter the price of item 3: "))
price4 = float(input("Enter the price of item 4: "))
price5 = float(input("Enter the price of item 5: "))

# Calculate the subtotal
subtotal = price1 + price2 + price3 + price4 + price5

# Calculate the sales tax
sales_tax = subtotal * sales_tax_rate

# Calculate the total
total = subtotal + sales_tax

# Display the results
print("Subtotal: $", subtotal)
print("Sales Tax: $", sales_tax)
print("Total: $", total)

# ----------------------------------------

5)
# Define the speed of the car
speed = 70  # miles per hour

# Calculate the distances for 6, 10, and 15 hours
distance_6_hours = speed * 6
distance_10_hours = speed * 10
distance_15_hours = speed * 15

# Display the results
print("The distance the car will travel in 6 hours is:", distance_6_hours, "miles")
print("The distance the car will travel in 10 hours is:", distance_10_hours, "miles")
print("The distance the car will travel in 15 hours is:", distance_15_hours, "miles")

# ----------------------------------------

6)
# Define the sales tax rates
state_sales_tax_rate = 0.05
country_sales_tax_rate = 0.025

# Ask the user to enter the amount of the purchase
purchase_amount = float(input("Enter the amount of the purchase: "))

# Calculate the state sales tax
state_sales_tax = purchase_amount * state_sales_tax_rate

# Calculate the country sales tax
country_sales_tax = purchase_amount * country_sales_tax_rate

# Calculate the total sales tax
total_sales_tax = state_sales_tax + country_sales_tax

# Calculate the total amount of the sale
total_amount = purchase_amount + total_sales_tax

# Display the results
print(f"Amount of Purchase: ${purchase_amount:.2f}")
print(f"State Sales Tax: ${state_sales_tax:.2f}")
print(f"Country Sales Tax: ${country_sales_tax:.2f}")
print(f"Total Sales Tax: ${total_sales_tax:.2f}")
print(f"Total of the Sale: ${total_amount:.2f}")

# ----------------------------------------

7)
# Ask the user for the number of miles driven
miles_driven = float(input("Enter the number of miles driven: "))

# Ask the user for the number of gallons of gas used
gallons_used = float(input("Enter the number of gallons of gas used: "))

# Calculate the miles per gallon
mpg = miles_driven / gallons_used

# Display the result
print(f"The car's miles per gallon (MPG) is: {mpg:.2f}")

# ----------------------------------------

8)
# Define the tip and sales tax rates
tip_rate = 0.18
sales_tax_rate = 0.07

# Ask the user to enter the charge for the food
food_charge = float(input("Enter the charge for the food: "))

# Calculate the sales tax
sales_tax = food_charge * sales_tax_rate

# Calculate the tip
tip = food_charge * tip_rate

# Calculate the total amount of the meal
total_amount = food_charge + sales_tax + tip

# Display the results
print(f"Charge for the food: ${food_charge:.2f}")
print(f"Sales tax (7%): ${sales_tax:.2f}")
print(f"Tip (18%): ${tip:.2f}")
print(f"Total amount: ${total_amount:.2f}")

# ----------------------------------------

9)
# Ask the user to enter a temperature in Celsius
celsius = float(input("Enter the temperature in Celsius: "))

# Convert Celsius to Fahrenheit
fahrenheit = (9 / 5) * celsius + 32

# Display the result
print(f"The temperature in Fahrenheit is: {fahrenheit:.2f}")

# ----------------------------------------

10)
# Define the quantities for 48 cookies
sugar_per_48 = 1.5
butter_per_48 = 1.0
flour_per_48 = 2.75
cookies_per_recipe = 48

# Ask the user how many cookies they want to make
desired_cookies = int(input("Enter the number of cookies you want to make: "))

# Calculate the scaling factor
scaling_factor = desired_cookies / cookies_per_recipe

# Calculate the required amount of each ingredient
sugar_needed = sugar_per_48 * scaling_factor
butter_needed = butter_per_48 * scaling_factor
flour_needed = flour_per_48 * scaling_factor

# Display the results
print(f"To make {desired_cookies} cookies, you need:")
print(f"{sugar_needed:.2f} cups of sugar")
print(f"{butter_needed:.2f} cups of butter")
print(f"{flour_needed:.2f} cups of flour")

# ----------------------------------------

11)
# Ask the user for the number of lions
num_lions = int(input("Enter the number of lions in the exhibit: "))

# Ask the user for the number of tigers
num_tigers = int(input("Enter the number of tigers in the exhibit: "))

# Calculate the total number of big cats
total_cats = num_lions + num_tigers

# Check if there are any cats in the exhibit to avoid division by zero
if total_cats == 0:
    print("There are no big cats in the exhibit.")
else:
    # Calculate the percentage of lions and tigers
    percentage_lions = (num_lions / total_cats) * 100
    percentage_tigers = (num_tigers / total_cats) * 100

    # Display the results
    print(f"Percentage of lions: {percentage_lions:.2f}%")
    print(f"Percentage of tigers: {percentage_tigers:.2f}%")

# ----------------------------------------

12)
# Define the details of the stock purchase
num_shares = 2000
purchase_price_per_share = 40.00
purchase_commission_rate = 0.03

# Define the details of the stock sale
sale_price_per_share = 42.75
sale_commission_rate = 0.03

# Calculate the total amount paid for the stock
total_purchase_amount = num_shares * purchase_price_per_share

# Calculate the commission paid when buying the stock
purchase_commission = total_purchase_amount * purchase_commission_rate

# Calculate the total amount received from selling the stock
total_sale_amount = num_shares * sale_price_per_share

# Calculate the commission paid when selling the stock
sale_commission = total_sale_amount * sale_commission_rate

# Calculate the amount of money Joe had left after selling the stock and paying both commissions
profit_or_loss = (total_sale_amount - sale_commission) - (total_purchase_amount + purchase_commission)

# Display the results
print(f"Amount of money Joe paid for the stock: ${total_purchase_amount:.2f}")
print(f"Commission paid when buying the stock: ${purchase_commission:.2f}")
print(f"Amount for which Joe sold the stock: ${total_sale_amount:.2f}")
print(f"Commission paid when selling the stock: ${sale_commission:.2f}")
print(f"Profit or Loss: ${profit_or_loss:.2f}")

if profit_or_loss > 0:
    print("Joe made a profit.")
elif profit_or_loss < 0:
    print("Joe lost money.")
else:
    print("Joe broke even.")

# ----------------------------------------

13)
# Ask the user to input the length of the row
length_of_row = float(input("Enter the length of the row (in feet): "))

# Ask the user to input the amount of space used by each end-post assembly
space_per_end_post = float(input("Enter the amount of space used by each end-post assembly (in feet): "))

# Ask the user to input the amount of space between the vines
space_between_vines = float(input("Enter the amount of space between the vines (in feet): "))

# Calculate the number of grapevines that will fit in the row
number_of_grapevines = (length_of_row - 2 * space_per_end_post) / space_between_vines

# Display the result
print(f"Number of grapevines that will fit in the row: {int(number_of_grapevines)}")

# ----------------------------------------

14)
# Ask the user for the principal amount originally deposited
principal = float(input("Enter the amount of principal originally deposited: "))

# Ask the user for the annual interest rate (as a percentage)
annual_interest_rate = float(input("Enter the annual interest rate (as a percentage): "))

# Convert the annual interest rate from percentage to decimal
annual_interest_rate_decimal = annual_interest_rate / 100

# Ask the user for the number of times per year that the interest is compounded
compounding_per_year = int(input("Enter the number of times per year that the interest is compounded: "))

# Ask the user for the number of years the account will be left to earn interest
years = int(input("Enter the number of years the account will be left to earn interest: "))

# Calculate the amount of money in the account after the specified number of years
amount = principal * (1 + annual_interest_rate_decimal / compounding_per_year) ** (compounding_per_year * years)

# Display the result
print(f"The amount of money in the account after {years} years is: ${amount:.2f}")
