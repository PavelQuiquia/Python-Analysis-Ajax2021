# Python-Analysis-Ajax2021

Visualization of players 'Ajax' Champion of the Eredivisie 20-21

These are the steps to get some analytics by players:

Using: 

- Get URL from chrome.
- Postman - to get the request code.
- Atom IDE to mimic the request from the website, and create the DB.
- Python Pandas - To analyze the data ad get some visuals.
- Python in Atom IDE - To analyze and get some visuals.

1. Get database from www.whoscored.com.
I will use the DB of players from 'Ajax' in the Eredivisie 20-21.
Link to webpage:
https://www.whoscored.com/Teams/130/Show/Netherlands-Ajax

2. Get the DB url from the website:
inspect -> Network -> XHR and 'copy as cURL (bash)' the Name that starts with 'GetPlayerstat...'

3. Get the python request code:
Enter to Postman (www.postman.com), download and create an account, then import:
Import -> raw text -> copy the cURL -> CodeSnippet -> Python-Requests
Copy the Python request

4.  Mimic the request in your IDE
Copy the python request in your IDE (I use Atom), and run to create the DB in CSV format
--> CHECK FILE: Getrequest.py

5. Work the DB
Use Jupyter IDE and Pandas to create some visualization of the DB created.
--> CHECK FILE: 
- Ajax Champion 20-21 Eredivisie.ipynb
- Ajax20.py
