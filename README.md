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