# LittleLemon - Restaurant Table Booking Web App
**LittleLemon** is a modern web application designed for customers to effortlessly book tables at a restaurant. It provides a simple and intuitive interface for users to check real-time availability, view the menu, and reserve tables—all within a few clicks.

Whether you're planning a casual lunch or a special evening out, LittleLemon ensures a smooth and hassle-free booking experience.

## Key Features

- **Simple Table Booking**: Users can select a date, time, and number of guests to easily reserve a table.
- **Real-Time Availability**: The app displays available tables in real-time, so customers only book when a table is free.
- **Menu Display**: Customers can browse the full restaurant menu with pricing and descriptions.
- **Responsive Design**: Fully optimized for both desktop and mobile devices.
- **Order History**: Keeps track of past reservations for easy reference.
- **User Authentication**: Users can sign up, sign in, and track their bookings for future visits.
- **Search and Filters**: Search for specific dishes on the menu, and apply filters for cuisine type or dietary restrictions.


## Screenshots

### Homepage
![Homepage](assets/Screenshot_171.png)

### Menu, Book Table, Open hours
![Menu, Book Table, Open hours](assets/Screenshot_172.png)

### Menu items
![Menu items](assets/Screenshot_173.png)

### Reservation page
![Reservation page](assets/Screenshot_174.png)

### Reservation record in database
![Reservation record in database](assets/Screenshot_176.png)


# run server 
* cd to dir. --> on terminal run --> 
``` 
python manage.py runserver
```
# make a booking
* go to book page --> add details --> make a booking

# open database on vs code terminal
# open restaurant_booking under tables
* cd to dir. --> on terminal run -->
```
python manage.py dbshell

        or

sqlite3 db.sqlite3
```
* It will open sql in terminal Then run sql commands  :-
```
DELETE FROM restaurant_booking WHERE first_name = 'Avinash';
```
```
.exit (to exit sql)
```

```
netstat -ano | findstr :8000

        output :- 
        TCP    127.0.0.1:8000     0.0.0.0:0     LISTENING       12345

taskkill /PID 12345 /F
Replace 12345 with your actual PID.
```

```
use requirements.txt
pip install -r requirements.txt

in terminal :-
venv\bin\activate
pip show django 
python manage.py runserver
sqlite3 db.sqlite3
deactivate
```