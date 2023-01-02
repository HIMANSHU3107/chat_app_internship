# chat_app_internship

# How do I get started?
## Prerequisites

  * Python 
  * MongoDB
  

## Setup

  * Clone the repo and navigate into the top-level directory.
  * Create a virtual environment (venv) for installing Python packages, then
  activate it and install all required packages:
  ```bash
  virtualenv venv
  .\venv\Scripts\activate.ps1
  pip install -r requirements.txt
  ```
  * Make sure that MongoDB is running: 
  * Create the database:
     internship_project
     and inside this we have three seperate collections:
    ```customerList - to store the list of customers
    agentList  - to store data related to agent
    messageList - to store the list of messages
    ```
  * Start the server: `python .\app.py`
  * Navigate to http://localhost:5000/customer_dashboard to see the Customer Dashboard
  interface.
  * Navigate to http://localhost:5000/admin/agent_dashboard to see the Admin Dashboard.
