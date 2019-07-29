# Overview
Ebazzar is an e-commerce database website with the purpose of selling electronic goods online.<br/>
The program uses:<br/>
* ***Front End*** : Html 5, Bootstrap<br/>
* ***Back End***  : Python<br/>
* ***Framework*** : Flask<br/>
* ***Database***  : MySQLdb<br/>

# To Run the Application
1. Install required libraries in order for the app to run. The list of libaries can be found in Libary Requirements.txt<br/>
   or you can skip this and install all the modules needed later when the system tells what module is misssing
2. Create a database on your localhost
3. Import ecommerce_DDL.sql into your database
4. Go to flaskDemo>>database.yaml and edit your connection profile
5. Go to flaskDemo>>_init_.py and edit the connection proxy to your database <br/>
   app.config['SQLALCHEMY_DATABASE_URI'] = 'your connection here'<br/>
6. Open your windows/anaconda terminal and move your destination folder to the folder that contains run.py.<br/>
   Example is '$cd .....\Ebazzar-Ecommerce-website'
7. Type 'python run.py' in the command line, it will output a website link, copy and paste that website link to a browser. <br/>
   In this step, if there is any libary that you did not import, there will be an error stating 'No Module name ....'

# Database Workflow
Below here is the ERD Diagram of Ebazzar Website.
<p align="center">
  <img src="https://github.com/AlbertSugi/Pictures/blob/master/Untitled%20Diagram%20(2).jpg"><br/>
</p><br/>

