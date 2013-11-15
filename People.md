People
===============
<h2>Get people

`GET /people.json` will return all people on the account.

```[
  {
    "id": 149087659,
    "identity_id": 982871737,
    "name": "Jason Fried",
    "email_address": "jason@37signals.com",
    "admin": true,
    "avatar_url": "https://asset0.37img.com/global/4113d0a133a32931be8934e70b2ea21efeff72c1/avatar.96.gif",
    "created_at": "2012-03-22T16:56:48-05:00",
    "updated_at": "2012-03-22T16:56:48-05:00",
    "url": "https://basecamp.com/999999999/api/v1/people/149087659-jason-fried.json"
  },
  {
    "id": 1071630348,
    "identity_id": 827377171,
    "name": "Jeremy Kemper",
    "email_address": "jeremy@37signals.com",
    "admin": true,
    "avatar_url": "https://asset0.37img.com/global/e68cafa694e8f22203eb36f13dccfefa9ac0acb2/avatar.96.gif",
    "created_at": "2012-03-22T16:56:48-05:00",
    "updated_at": "2012-03-22T16:56:48-05:00",
    "url": "https://basecamp.com/999999999/api/v1/people/1071630348-jeremy-kemper.json"
  }
]```

<h2>Get person

<ul>
  <li>`GET /people/1.json` will return the specified person.</li>
  <li>`GET /people/me.json` will return the current person.</li>
  
  

Fastservice API
