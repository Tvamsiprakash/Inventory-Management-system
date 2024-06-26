INVENTORY MANAGEMENT SYSTEM

This Python script manages an inventory system, allowing users to purchase products and update the inventory accordingly. It also logs sales transactions. The inventory data is stored in a JSON file (Records.json), and sales are recorded in a text file (Sales.txt).

Features

    Menu Display: Shows the available products, their prices, and quantities.
    User Interaction: Prompts the user for their details and purchase information.
    Inventory Update: Updates the inventory based on the user's purchase.
    Sales Logging: Records the transaction details in a sales file.

File Structure

    Records.json: Contains the inventory data.
    Sales.txt: Logs the sales transactions.
    inventory_management.py: The main script for managing the inventory and processing purchases.

 How It Works

    Load Inventory:
        The script reads the inventory data from Records.json and converts it into a dictionary.
    Display Menu:
        The available products, their prices, and quantities are displayed to the user.
    User Input:
        The user is prompted to enter their name, email, phone number, product ID, and the desired quantity.
    Inventory Check:
        The script checks if the requested quantity is available:
            If available, the purchase is processed, the inventory is updated, and the transaction is logged.
            If not available, the user is informed about the available quantity and given the option to purchase the available quantity.
    Update Inventory:
        The updated inventory is saved back to Records.json.
    Log Transaction:
        The transaction details are appended to Sales.txt.
snaps:
3 rd customer
![image](https://github.com/Tvamsiprakash/Inventory-Management-system/assets/134200606/b71849be-5381-48ee-b045-f951df430046)
updating json which has prouct details
![image](https://github.com/Tvamsiprakash/Inventory-Management-system/assets/134200606/e69c1279-4450-4b97-a864-e9eaef162d75)
customer details text file
![Screenshot 2024-06-26 122819](https://github.com/Tvamsiprakash/Inventory-Management-system/assets/134200606/6a227a79-beb3-409f-8a23-0c49bdc9ccb0)
customer details csv file
![image](https://github.com/Tvamsiprakash/Inventory-Management-system/assets/134200606/e44717b5-4b72-443b-ac14-c4315f78d442)



