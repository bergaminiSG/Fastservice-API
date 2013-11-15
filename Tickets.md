Tickets
===============


<h2>GET Tickets 

`GET /Tickets.json` will show all the tickets assigned to e specified user.

```
[
  {
    "id": 149087659,
    "identity_id": 982871737,
    "User": "Mirco Angelini",
    "email_address": "mirco.angelini@centrocomputer.it",
    "admin": true,
    "avatar_url": "https://fs.centrcomputer.it/images/mangelini.gif",
    "created_at": "2013-11-22T16:56:48-05:00",
    "updated_at": "2013-11-22T16:56:48-05:00",
    "url": "https://fs.centrcomputer.it/api/v1/people/1071630348-mirco-angelini.json"
  },
  {
    "id": 1071630348,
    "identity_id": 827377171,
    "name": "Tommaso Vecchiattini",
    "email_address": "tommaso.vecchiattini@centrocomputer.it",
    "admin": true,
    "avatar_url": "https://fs.centrcomputer.it/images/tvecchiattini.gif",
    "created_at": "2013-11-22T16:56:48-05:00",
    "updated_at": "2013-11-22T16:56:48-05:00",
    "url": "https://fs.centrcomputer.it/api/v1/people/1071630348-tommaso-vecchiattini.json"
  }
]
```
<h2>Get person

<ul>
  <li>`GET /people/1.json` will return the specified person.</li>
  <li>`GET /people/me.json` will return the current person.</li>
  
  

Fastservice API
