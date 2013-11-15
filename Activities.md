Activities
===============

<h2> GET Activities

`GET /Activities.json` will return all the activities executed by a Fastservice user account, from a specified date-time. 

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
    "url": "https://fs.centrocomputer.it/api/v1/Activities/Activities.json"
```


<h2> POST Activity

`POST /Activity.json` will create an activity for a specified user account. 

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
