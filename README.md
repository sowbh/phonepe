# Phonepe Pulse Data Visualization and Exploration: A User-Friendly Tool Using Streamlit and Plotly.
Technologies used: Github Cloning, Python, Pandas, MySQL, mysql-connector-python, Streamlit, and Plotly.
Domain: Fintech

  The Phonepe pulse Github repository contains a large amount of data related to various metrics and statistics. The goal is to extract      this data and process it to obtain insights and information that can be visualized in a user-friendly manner.

  Approach:
  1. Data extraction: Clone the Github using scripting to fetch the data from the Phonepe pulse Github repository and store it in a           suitable format such as CSV or JSON.
  2. Data transformation: Use a scripting language such as Python, along with libraries such as Pandas, to manipulate and pre-process the     data. This may include cleaning the data, handling missing values, and transforming the data into a format suitable for analysis and       visualization.
  3. Database insertion: Use the "mysql-connector-python" or "sqlite3" library in Python to connect to a MySQL database and insert the 
    transformed data using SQL commands.
  4. Dashboard creation: Use the Streamlit and Plotly libraries in Python to create an interactive and visually appealing dashboard.          Plotly's built-in geo map functions can be used to display the data on a map and Streamlit can be used to create a user-friendly            interface with multiple dropdown options for users to select different facts and figures to display.
  5. Data retrieval: Use the "mysql-connector-python" library to connect to the MySQL database and fetch the data into a Pandas               dataframe. Use the data in the dataframe to update the dashboard dynamically.
  6. Deployment: Ensure the solution is secure, efficient, and user-friendly. Test the solution thoroughly and deploy the dashboard           publicly, making it accessible to users.

Run this code in any of the environment such as vscode, jupyter notebook or google-colab after installing the necessary libraries required in this project. 

Here, for storing the data we have used an alternative of mysql workbench ie; sqlite3. To view the database file;
 i.kindly install DB Browser for SQLite
 ii.download the phonepe_pulse.db from the notebook and copy to your respective project directory
 iii.click on open database and select the db file(phonepe_pulse.db)
 iv.click on browse data to see all 6 tables present in the db file(phonepe_pulse.db).

To run pp.py (your_filename.py) using streamlit, type in the terminal (works only in vscode):
Streamlit run pp.py (your_filename.py)
You can now view your Streamlit app in your browser.

  Local URL: http://localhost:8501
  Network URL: http://192.168.0.106:8501

Output:


![phonepe1](https://github.com/sowbh/phonepe/assets/95527211/76b33a09-d5ff-4621-8e3e-f284d05bcc81)


![phonepe2](https://github.com/sowbh/phonepe/assets/95527211/b1d556b1-fc0f-45ad-9659-20d47d03e2a5)


![phonepe3](https://github.com/sowbh/phonepe/assets/95527211/4b706d09-da17-4257-aacc-7d81fb9e2068)
