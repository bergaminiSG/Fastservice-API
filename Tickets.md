Tickets
===============


<h2>GET Tickets

`GET /Tickets.json` will show all the tickets assigned to e specified user.

```
[
  {
    "TicketID": 149087659,
    "UserID": 871737,
    "User": "Mirco Angelini",
    "EXTCode": "2013A00000234",
    "created_at": "2013-11-22T16:56:48-05:00",
    "updated_at": "2013-11-22T16:56:48-05:00",
    "url": "https://fs.centrcomputer.it/api/v1/tickets/Tickets.json"
  },
  {
    "TicketID": 149087660,
    "UserID": 871740,
    "User": "Mirco Angelini",
    "EXTCode": "2013A00000240",
    "created_at": "2013-11-22T16:56:48-05:00",
    "updated_at": "2013-11-22T16:56:48-05:00",
    "url": "https://fs.centrcomputer.it/api/v1/tickets/Tickets.json"
  }
]
```

<h2> GET Ticket

`GET /Ticket.json` will show the ticket detail assigned to e specified user.

```
    "TicketID": 149087659,
    "UserID": 871737,
    "User": "Mirco Angelini",
    "EXTCode": "2013A00000234",
    "TicketDate: "2013-11-22T16:56:48-05:00"
    "TicketStatus: "1"
    "created_at": "2013-11-22T16:56:48-05:00",
    "updated_at": "2013-11-22T16:56:48-05:00",
    "url": "https://fs.centrcomputer.it/api/v1/tickets/Ticket.json"
```

