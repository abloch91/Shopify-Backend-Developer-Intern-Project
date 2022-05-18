# Shopify-Backend-Developer-Intern-Project


Project Introduction

This is my submission for the Shopify Fall 2022 Backend Developer Internship Challenge.  I have created an      inventory tracking application for a company called AMB Logistics.  This application has the capability to create inventory items, edit them, delete them and view a list of them.  Additionally, I have added a feature that gives you the ability to create locations and assign inventory to specific locations.



Instructions:



Setting up the Environment:

  1)Download & Install Python 3.10
  
  2)Download & Install SQLite3
  
  3)Download & Install Git
  
  4)Install the following
  
      Python3.9-venv
  
  5)Clone the repository
  
      https://github.com/abloch91/Shopify-Backend-Developer-Intern-Project.git
  
  6)Go to the repository directory
    	
      cd Shopify-Backend-Developer-Intern-Project
 
  7)Create a python virtual environment
    	
      python3 -m venv venv
  
  8)Activate the python virtual environment
	    
      source venv/bin/activate
  
  9)Run the application	
    	
      python ShopifyDeveloperInternChallenge.py

Using The Application:
  
  1)On the top left screen go to file, account and login using the following credentials
    	
      Username: admin
    	
      Password: admin
  
  2)On the top left screen, click the “Inventory” dropdown for CRUD functionalities and additional features
      
      Select “Add new” to add a new product that includes the product name, product quantity and product price
	    
      Select “View” to view products, search products, reset products and delete products
      
      Select “Add New Location” to add a new warehouse or location and include the location name and location address
      
      Select “Assign Inventory Location” to assign inventory to a location using the location name, product name and product quantity
      
      Selection “View Locations” to view all locations including the location names, products the location has along with product quantities
