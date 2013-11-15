Activities
===============

<h2> GET Activity

`GET /Activity.json` will receive an activity executed by a Fastservice user account. 

This method il mainly used by outer back-end systems to receive back information of actvities executed. 
A typical use is a 

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

`POST /Activity.json` will send an Activity to an Account.

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
