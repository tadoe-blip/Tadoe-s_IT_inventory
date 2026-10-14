
approved_models = ("MacBook Pro", "Dell XPS", "ThinkPad")
device_inventory = []

print("Welcome to IT Inventory Tracker!")

while True:
    print("")
    print("IT Inventory Menu")
    print("1. Add Device")
    print("2. Remove Device")
    print("3. View Inventory")
    print("4. Exit")

    choice = input("Enter your choice: ")

    if choice == "1":
        print("")
        print("Choose a device:")
        print("1. MacBook Pro")
        print("2. Dell XPS")
        print("3. ThinkPad")

        number = input("Enter device number: ")

        if number == "1":
            device = "MacBook Pro"
        elif number == "2":
            device = "Dell XPS"
        elif number == "3":
            device = "ThinkPad"
        else:
            device = ""

        if device in approved_models:
            device_inventory.append(device)
            print("Device added:", device)
        else:
            print("Invalid device choice.")

    elif choice == "2":
        print("")
        print("Current inventory:", device_inventory)

        device = input("Enter device name to remove: ")

        if device in device_inventory:
            device_inventory.remove(device)
            print("Device removed:", device)
        else:
            print("Device not found.")

    elif choice == "3":
        print("")
        print("Current inventory:")
        print(device_inventory)

    elif choice == "4":
        print("Thank you for using IT Inventory Tracker!")
        break

    else:
        print("Invalid choice. Please try again.")
