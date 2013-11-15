Activities
===============

<h2> GET Activity

`GET /Activity.json` will receive an activity executed by a Fastservice user account. 

This method il mainly used by outer back-end systems to receive back information of actvities executed. 
For example: a customer post a ticket to a supplier, then he get the supplier's activity back.

```
    "TicketID": 149087659,
    "EXTCode": "2013A00000234",
    "ActivityID": 12345
    "UserID": 871737,
    "User": "Mirco Angelini",
    "ActivityDate": "2013-11-22T16:56:48-05:00"
    "TicketStatus": "1"
    "...": "..."    
    
    "created_at": "2013-11-22T16:56:48-05:00",
    "updated_at": "2013-11-22T16:56:48-05:00",
    "url": "https://fs.centrocomputer.it/api/v1/Activities/Activity.json"
```


<h2> POST Activity

`POST /Activity.json` will send an activity to Fastservice. This method can be invoked by mobile workforce users to send back the activity done. informations   

```
    "TicketID": 149087659,
    "EXTCode": "2013A00000234",
    "ActivityID": 12345
    "UserID": 871737,
    "User": "Mirco Angelini",
    "EXTCode": "2013A00000234",
    "ActivityDate": "2013-11-22T16:56:48-05:00"
    "TicketStatus": "1"
    "...": "..."    
    
    "created_at": "2013-11-22T16:56:48-05:00",
    "updated_at": "2013-11-22T16:56:48-05:00",
    "url": "https://fs.centrocomputer.it/api/v1/Activities/Activity.json"
```
