# BodhiBookingService
Manage Booking details

This Service is used to manage booking details of Bodhi application.

#sequelize-cli commands
```
 npx sequelize-cli init  

 --> create following folders:
config, contains config file, which tells CLI how to connect with database
models, contains all models for your project
migrations, contains all migration files
seeders, contains all seed files



```
## Sample Booking request
#### Create Booking:
```
     { 
        "patient_email_id": "patient1@usa.com",   
        "clinic_id":"5eab42762d4e1b4db8fd6a8c",
        "doctor_id":"5eab42762d4e1b4db8fd6a8d",
        "date": "2019-01-01",
        "time": "10:00",
        "status":"BOOKED"
    }
```