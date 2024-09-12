# Webbed 
### By ayush ghimire


## Owasp top 10

### Broken Access control 
--- Description - access control enforces policy that users cannot act of outside of their intended permissions.Some of these includes Api unthuorized access due to CORS configurations, giving consent to someboady else account by giving unique id ,maniplating JSON web token access control token or a cookie, bypassing access control checks by modifying the URl, acting as user without logging as a user, and manipulating metadata.

--- How to prevent - To prevent the Access Control Every developer should Rate limit API and controller access to minimize the harm from automated attack tooling, disable web server directory listing and ensure file metadata, are not present within the web, the model layer should put a record ownership rather than giving permission for any CRUD operatons, there should be a short timespan for the JWt token so that the attacker can not manipulate , alerting on a inappropriate access by logging all the failures attempt.


### 


