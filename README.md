Web services to integrate doctors calendar with Notable.

## Step 0
Clone the repository on your local machine
```
git clone https://github.com/naveen16/Notable.git
```
## Step 1:
```
cd Notable
sqlite3 notabledb.sqlite < db/db.sql
python app.py
```
## Step 2:

Open browser and point to http://localhost:5000/

Routes to test:

Get all doctors:
http://localhost:5000/doctors

Get Appointments for a doctor on a date(example below):
http://localhost:5000/appointments/3/12-10-2018

Create an Appointment:
http://localhost:5000/appointment

Delete an Appointment(need appiontment id to delete):
http://localhost:5000/deleteAppt/6

## Step 3:
Click “Test Notable Services” button to test the creation of appointments. 

## Dependencies
Need python, flask, sqlite
