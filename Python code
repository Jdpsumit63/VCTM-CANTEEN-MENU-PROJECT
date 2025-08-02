# Define the V.C.T.M. Canteen Menu
menu = {
    'Tea': 10,
    'Coffee': 20,
    'Pizza': 49,
    'Maggi': 50,
    'Burger': 35,
    'Samosa': 15,
    'Bread Pakoda': 20,
    'Momoj': 40,
}

# Greet
print("Welcome to V.C.T.M. Canteen")
print("Menu:")
for item, price in menu.items():
    print(f" {item}: Rs{price}")

order_total = 0
order_items = []

while True:
    item = input("Enter the item you want to order: ").strip().title()
    if item in menu:
        order_total += menu[item]
        order_items.append(item)
        print(f"{item} added to your order.")
    else:
        print(f"{item} is not available in the menu.")

    another_order = input("Do you want to order another item? (Yes/No): ").strip().lower()
    if another_order != "yes":
        break

# Print Bill
print("\nOrder Summary:")
for ordered_item in order_items:
    print(f"- {ordered_item}: Rs{menu[ordered_item]}")
print(f"Total Amount to Pay: Rs {order_total}")
