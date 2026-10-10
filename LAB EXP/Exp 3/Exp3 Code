
import numpy as np

# Load data from CSV file
# Columns: bedrooms, square footage, sale price
house_data = np.array([
    [3, 1500, 250000],
    [5, 2500, 450000],
    [4, 2000, 350000],
    [6, 3000, 550000],
    [5, 2800, 500000]
])

# Select houses with more than four bedrooms
selected_houses = house_data[house_data[:, 0] > 4]

# Extract sale prices (third column)
sale_prices = selected_houses[:, 2]

# Calculate average sale price
if len(sale_prices) > 0:
    average_price = np.mean(sale_prices)
    print("Average sale price:", average_price)
else:
    print("No houses with more than four bedrooms.")
