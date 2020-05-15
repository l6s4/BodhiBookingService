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
        "time_slot": "10:00",
        "status":"BOOKED"
    }
```
## migration
```
$ ./node_modules/.bin/env-cmd -f ./config/linux.env npx sequelize-cli db:migrate
```