# Ecommerce platform with ML (E-Commerce Website)

--------------------------------------------!!!!!!!!!!!!!!!!!!!importent note!!!!!!!!!!!!!!!!!!---------------------------
please take into considertaion that this project is still a working progress and modification and fixes are still adding untill viva is done. this is demo project that was use to do a vulanarability assesment assigmnet. this project is solery for personal use only.
please take note that delivring a ML product in week is a heavy task that we took amid with our current semester time manegemt crisis. this project was developed sorley to do the assesment only that.the technical paper along with the project will give inside to the demo fuctionalities. note to madam, we tired our best to deliver a product to your requirements with ML!. use this project as a reference only.


.

### About

In this projects a user can visit the websites, registers and login to the website. They can check all the products available for shopping, filter and search item based on different categories, and then add to cart. They can add multiple item to the cart and also plus or minus the quantity in the cart. Once the cart is updated, the user can proceed to checkout and click the credit card payment details to proceed. Once the payment is success the orders will be placed and users will be able to see the orders details in the orders section along with the shipping status of the product.

The admin also plays an important role for this project as the admin is the one responsible for adding any product to the store, updating the items, removing the item from the store as well as managing the inventory. The admin can see all the product orders placed and also can mark them as shipped or delivered based on the conditions.

One of the best functionality that the projects include is mailing the customers, so once a user registers to the website, they will recieve a mail for the successful registration to the website, and along with that whenever a user orders any product or the product got shipped from the store, then the user will also receive the email for its confirmation.
Sometimes, if the user tried to add any item which is out of stock, them they will get an email one the item is available again the stock.

## Highlights :--

### Technologies used:-
1. Front-End Development:
- HTML
- CSS
- Javascript
- BootStrap

2. Back-End Development:
- Java [JDK 8+]
- JDBC
- Servlet
- JSP

3. Database:
- MySql

 --------------------------Database Initialization-----------------------------
Open MySQL Command Prompt or MySQL Workbench.

1.Log in to the MySQL administrator user:

sh
Copy code
mysql -u <username> -p
Enter the password if prompted.

Execute the MySQL Query:

Copy and paste the provided SQL queries from the text file into the MySQL command prompt or MySQL Workbench to create and initialize the database.

-------------------Create a Gmail account or log in to an existing account in a browser.-----------------

2. Enable 2-step verification:

Go to Google Security and ensure that 2-step verification is enabled.
Generate an App Password:

Go to Google App Passwords and enter your account password if asked.
In the "Select App" section, choose "Other (Custom name)" and enter "Green Store."
Click "Generate" to get a 16-digit app password. Copy and save this password for future use. Do not share this password with anyone.
Importing and Running the Project Through Eclipse EE


---------------Open Eclipse Enterprise Edition.----------------------

3.Go to Java Resources > src > and update the following:
db.username and db.password with your MySQL credentials.
mailer.email and mailer.password with the email and app password generated earlier.
Run Maven Build:

Right-click on the project, select Run As > Maven Build.
In the goals field, enter clean install, then click Apply and Run.
Configure Build Path:

Right-click on the project, select Build Path > Configure Build Path.
Go to Libraries and update any libraries if there are red marks, then click Finish.
Update Project:

Right-click on the project, select Maven > Update Project.
Check Force Update, then click Apply and Close.
Tomcat Configurations:

@@@@@@@(If Tomcat Server is not configured in Eclipse: 
Right-click on the project, select Run As > Run On Server.
Manually define a new server, select the Tomcat version (v9.0+), and set the installation location if asked.
Add the current project, then click Finish.)@@@@@@@

@@@@@@@@(If Tomcat Server is already configured in Eclipse:
Right-click on the project, select Run As > Run On Server.
Select the Tomcat version, add the project, then click Finish.
Alternatively, go to the server tab, select the Tomcat server, and use the debug or run button to start the project.)@@@@@@@


-------------------Check the Running Site:-------------------------------

4. Open http://localhost:8080/project_name/ to see the running site.
Change Port if Necessary:

If you encounter a "port already in use" error, open the server tab.
Double-click on the Tomcat server, go to Ports, and change the Http/1.1 port to 8083.
Save and start the server. Access the project at http://localhost:8083/my_project/.
Default Credentials:


----------extra -----

Admin username: admin@gmail.com
Admin password: admin
User username: guest@gmail.com
User password: guest

