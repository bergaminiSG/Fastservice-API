Activities
===============

GET Activities
---------------

`GET /Activities` Returns a list of activities

##### Parameters #####

| Name               | Type    | Optional | Description  |
| ------------------ |:-------:|:--------:|:-------------|
| **UserId**         | Integer | Yes      | used for retrieve only activities for the selected user |
| **ActivityId**     | Integer | Yes      | used for retrieve a single activity |
| **onlyNotSynched** | Boolean | Yes      | used for retrieve only activities not synchronized with external systems |

##### Returns #####
```
Status: 200 OK
```

```json
[
    {
        "ActivityID": 24,
        "TicketID": 4644,
        "TicketCode": "2013AXXXXXX",
        "TicketExtCode": "00000000-0000-0000-0000-00000000000",
        "CustomerID": 850,
        "CustomerExtCode": "00000000-0000-0000-0000-00000000000",
        "UserID": 38,
        "UserExtCode": "00000000-0000-0000-0000-00000000000",
        "Date": "02/12/2013",
        "TimeStart": "10:00",
        "TimeStop": "16:30",
        "TimePause": "01:00",
        "TimeTrip": "02:00",
        "Category1": {
            "lookupType": 0,
            "ID": 4,
            "Description": "Software",
            "timeCreate": "2013-12-19 11:06:52.488",
            "timeModified": "2013-12-19 11:06:52.488"
        },
        "Category2": {
            "lookupType": 1,
            "ID": 2,
            "Description": "Avanzato",
            "timeCreate": "2013-12-19 11:06:52.488",
            "timeModified": "2013-12-19 11:06:52.488"
        },
        "Workplace": {
            "lookupType": 3,
            "ID": 1,
            "Description": "OnSite",
            "timeCreate": "2013-12-19 11:06:52.488",
            "timeModified": "2013-12-19 11:06:52.488"
        },
        "Billable": {
            "lookupType": 2,
            "ID": 1,
            "Description": "Si",
            "timeCreate": "2013-12-19 11:06:52.488",
            "timeModified": "2013-12-19 11:06:52.488"
        },
        "Title": "Intervento",
        "Description": "Descrizione intervento",
        "Note": null,
        "Rate": null,
        "CloseTicket": "Si",
        "Spares": [
            {
                "PartNumber": "xxxxxx",
                "Description": "Spare desc",
                "Brand": "insert brand",
                "Cost": "40,85",
                "Price": "51,62",
                "Quantity": 2,
                "Warranty": "True",
                "Billable": 2,
                "ERPCode": "abcdef"
            },
            {
                "PartNumber": "xxxxxx",
                "Description": "Spare desc",
                ...
            }
        ],
        "Emails": "example@email.it",
        "CreationDate": "2013-12-03 16:57:10.957",
        "ModifiedDate": "2013-12-03 17:00:48.813",
        "Sign": "<binary_data>"
    },
    {
        "ActivityID": 24,
        "TicketID": 4644,
        "TicketCode": "2013AXXXXXX"
        ...
    }
]
```


POST Activity
---------------

`POST /Activity` Create a new activity for a specified user and ticket. 

##### Request object #####
A JSON object representing the activity to create

```json
{
        "UserID": 38,
        "AccountId": 24,
        "TicketID": 4644,
        "Category1": 3,
        "Category2": 1,
        "Workplace": 7,
        "Billable": 2,
        "Date": "02/12/2013",
        "TimeStart": "10:00",
        "TimeStop": "16:30",
        "TimePause": "01:00",
        "TimeTrip": "02:00",
        "Title": "Intervento",
        "Description": "Descrizione intervento",
        "Note": "inserire note",
        "CloseTicket": "Si",
        "Spares": [
            {
                "PartNumber": "xxxxxx",
                "Description": "Spare desc",
                "Brand": "insert brand",
                "Cost": "40,85",
                "Price": "51,62",
                "Quantity": 2,
                "Warranty": "True",
                "Billable": 2,
                "ERPCode": "abcdef"
            },
            {
                "PartNumber": "xxxxxx",
                "Description": "Spare desc",
                ...
            }
        ],
        "Emails": ["example@email.it", "example2@email.it"],
        "Sign": "<binary_data>",
        "CreationDate": "2013-12-03 16:57:10.957",
        "ModifiedDate": "2013-12-03 17:00:48.813"
}
```

##### Returns #####
```
Status: 200 OK
```
