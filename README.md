# Automate_catalog_updating_with_python
 an online fruits store needs to develop a system that will update the catalog information with data provided by its suppliers. The suppliers send the data as large images with an associated description of the products in two files (.TIF for the image and .txt for the description). The images need to be converted to smaller jpeg images and the text needs to be turned into an HTML file that shows the image and the product description. The contents of the HTML file need to be uploaded to a web service that is already running using Django. You also need to gather the name and weight of all fruits from the .txt files and use a Python request to upload it to the Django server.

Firstly the problem broken down into smaller phases and then eventually into even smaller pieces
that you can solve. The project then built using smaller pieces into a larger solution. 

Project phases:
1) Write a script that summarizes and processes sales data into different categories
2) Generate a PDF using Python
3) Automatically send a PDF by email
4) Write a script to check the health status of the system


Project steps and reason for code: 

1) Given a bunch of images and descriptions of each of the new products, 
2) Upload the new products to your online store. 
3) Images and descriptions should be uploaded separately, using two different web endpoints.
4) Send a report back to the supplier, letting them know what you imported.
5) Since this process is key to your business's success, you need to make sure that it keeps 
running! So, you’ll also:
- Run a script on your web server to monitor system health.
- Send an email with an alert if the server is ever unhealthy.
