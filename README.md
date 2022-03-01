# AI-Data-Warehouse-for-Students-Release-3

It is in interactive desktop based application, created using Python and PostgreSQL, OpenCV and Tesseract for text extraction.

## Release 3 features:
   
   1. Primary Key Integration: Now User table has primary key.
   2. Secured Login:           Now Password stored in database in a hashed form, provides more security.
   3. Robust Login:            Now login count is stored in the database. So someone must have to wait till 2 minutes for wrong credentials. Closing the program and relogin is not an option anymore.
   5. Timer Display:           Waiting Time for incorrect attempt is display on screen.
   6. Some minor logic enhancement.

## Release 2 features:
   
   1. Text to Speech login: Takes command from microphone, if matched with credential, login successful.
   2. Modular approach:     All operations kept in seperate files.
   3. Little UI enhancement: Shows red for unsuccessful login, green for successful login
   
## Release 1 features:

### Main features:

1. Takes input through Camera also from a Image file saved in Desktop/Laptop.

### Other features:

1. Login guard - After 3 incorrenct attemps, Session got Suspended for 2 minutes.                  
2. Desktop Notification - It can send desktop notification for certain operations.                  
3. Database Inheritance - Implemented the concept of RDBMS as well as ORDBMS.                  
4. Bulk Insertion - Transfer data from one table to another table using SQL Query.
