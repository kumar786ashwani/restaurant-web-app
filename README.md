# Silver Leaf - Restaurant Web Application
A Restaurant Web Application with **Table Booking, Online Food Ordering and Delivery Tracking.**<br/>

# Brief Description
Silver Leaf is a web-based application that is operated on a web server with its data being retained in a database. It is designed to enable the registered customer to reserve a table at the restaurant at a specified time in accordance with its availability, view and order the offered food item of their choice, and track the delivery of their order. <br/> 
Since the Internet provides a wider range of customers, the application will provide the restaurant with a chance to increase their profits while customers can avail the restaurant's services at the comforts of their homes.

# How to install our project <br/>

First, clone this repository and create a virtual environment using:
```
python -m venv venv
```
Activate the virtual environment:
```
./venv/Scripts/activate
```
Install the required packages using: <br/>
```
pip install -r requirements.txt
```

Create an Authy Application and grab your API Key https://www.twilio.com/console/authy/applications <br/>
Edit `config.py` and update the API key with your application key. Create a secret key for managing sessions. <br/>

`cd` to the location of the cloned repository and run the command:
```
python run.py
```
Copy `http://127.0.0.1:5000/` and paste it in the address bar of a browser.

