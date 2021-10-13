# Automate_catalog_updating_with_python
An online fruits store needs to develop a system that will update the catalog information with data provided by its suppliers. The suppliers send the data as large images with an associated description of the products in two files (.TIF for the image and .txt for the description). The images need to be converted to smaller jpeg images and the text needs to be turned into an HTML file that shows the image and the product description. The contents of the HTML file need to be uploaded to a web service that is already running using Django. Need to gather the name and weight of all fruits from the .txt files and use a Python request to upload it to the Django server.

Firstly the problem broken down into smaller phases and then eventually into even smaller pieces
that can solved. The project then built using smaller pieces into a larger solution. 

## Project phases:
1) Write a script that summarizes and processes sales data into different categories
2) Generate a PDF using Python
3) Automatically send a PDF by email
4) Write a script to check the health status of the system


## Project steps and reason for code: 

1) Create a python script to process the supplier images (products) to company specifications
2) Images and descriptions should be uploaded separately, using two different web endpoints.
3) Upload the modified images online (to the web server) that is handles the fruit catalog.
4) create a python script that automates POST the fruit images and their respective description
  in JSON format
5) Generate a PDF report and send it through email to supplier to acknowledge reciept.
6) Process is key to business's success, A Health Check is required. Included are:
- Run a script on your web server to monitor system health.
- Send an email with an alert if the server is ever unhealthy.
