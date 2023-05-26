# Product-Inventory-System

The Product Inventory System showcases the creation of an inventory and an invoice, along with their associated functionalities. It allows for the addition of products to the inventory and the creation of an invoice with invoice items.

# Code Overview
The provided code consists of the following components:

Inventory: An inventory class that manages a collection of products. It provides methods to add products, find products by their unique identifier, and display all products in the inventory.

Product: A class representing a product. Each product has a unique product code, a name, a price, and a quantity.

Invoice: An invoice class that represents a customer invoice. It allows for the addition of invoice items and provides a method to display the products sold.

InvoiceItem: A class representing an item in an invoice. It associates a product with a quantity.

Program: The main entry point of the application. It demonstrates the usage of the inventory and invoice management system by creating an inventory, adding products to it, creating an invoice, adding invoice items, and displaying the products sold.

# Usage
To use the Inventory and Invoice Management System, follow these steps:

Ensure that the necessary dependencies and classes (Inventory, Product, Invoice, InvoiceItem) are implemented and available.

Create an instance of the Inventory class.

Create instances of the Product class to represent the available products. Provide the necessary details such as product code, name, price, and quantity.

Add the created products to the inventory using the AddProduct method.

Create an instance of the Invoice class.

Create instances of the InvoiceItem class, associating each item with a product from the inventory and specifying the quantity.

Add the created invoice items to the invoice using the addToInvoice method.

Display the products in the inventory using the displayAllProduct method of the inventory.

Display the products sold in the invoice using the displayProductSold method of the invoice.

# Notes
Please note that the provided code snippet is a simplified implementation to demonstrate the usage of the inventory and invoice management system. In a real-world scenario, additional error handling, input validation, and data persistence mechanisms may be required.
