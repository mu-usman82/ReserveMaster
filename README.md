# ReserveMaster 
### About:
This project is to book your tickets, search its availability and check your booked seats from your account. You can also checkc listed trains, their timings with the fare. 
### Online Train Information and Booking
<span style="color:blue">**This Website is built for following purpose:-**</span>
- Check Vehicle Schedules
- Find Trains
- Check Seat Availability
- Train Schedules
- Fare Inquiry
- Trains Connecting Stations
- Online Seat Booking
- Booking History

### Software And technologies used 
- : Git
- : Java JDK 8+ 
- : Eclipse EE 
- : Apache Maven
- : Tomcat v8.0+ 
- : Oracle (SQL) / SQL PLUS
- : Oracle SQL Developer

### DB initialization

STEP 1: Open SQL Plus OR SQL Developer

STEP 2: Login and connect to database using administrator username and password

STEP 3 :Execute the SQL command first to create a new user

STEP 4: Now execute the sql query to create CUSTOMER and ADMIN tables in the DB. Now add some values in those tables.

STEP 5: Execute SQL query to check wheather the tables are created successfully

Note: If any of the above commands fails, please try to fix it first and then proceed to next step
	
### ====== Importing and Running the Project Through Eclipse EE ===========
Step 0: Open Eclipse Enterprise Edition. [Install if not available](https://www.youtube.com/watch?v=8aDsEV7txXE)

Step 1: Click On File > Import > Git > Projects From Git > Clone Uri  > Paste The Repository Url: ```https://github.com/shashirajraja/Train-Ticket-Reservation-System.git``` > Next > Select Master Branch > Next > Finish

Step 2.A: Right Click on Project > Run as > Maven Build > In the goals field enter "clean install" > apply > run

Step 2.B: Right Click On Project > Build Path > Configure Build Path > Libraries > Remove And Update Any Libraries With Red Mark > Finish

Step 3: [Only if Tomcat v8.0 is not Configured in Eclipse]: Right Click On Project > Run As > Run On Server > Select Tomcat v8.0 > (Select Tomcat V8.0 Installation Location If Asked) Next > Add <project-name> > Finish

Step 4: In The Server Tab > Double Click On Tomcat Server > Ports  > Change The Port Number For Http/1.1 To 8083 > Close And Save

Step 5: Right Click On Project > Run As > Run On Server > Select Tomcat V8.0 > Next > Add All> Done

Step 6: Check Running The Site At  <a Href="Http://localhost:8083/trainbook/">http://localhost:8083/trainbook/</a>

Step 7: Default Username And Password For Admin Is "admin@demo.com" And "admin"

Step 8: Default Username And Password For User Is "shashi@demo.com" And "shashi"

#### Contributions are much appreciated :)
