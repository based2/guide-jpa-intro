https://openliberty.io/guides/jpa-intro.html#performing-crud-operations-using-jpa
https://github.com/OpenLiberty/guide-jpa-intro

mvn install liberty:start-server

Frontend
http://localhost:9090/

http://localhost:5050/
http://localhost:5050/eventmanager.jsf
http://localhost:5050/eventmanager.xhtml
http://localhost:5050/images/openliberty.png -> errors in the file
http://localhost:5050/css/stylesheet.css

Backend
http://localhost:9080/
http://localhost:5050/events

Create event
POST
Content-type application/x-www-form-urlencoded
name=AAAA&location=BBBB&time=today

Get alls
GET
 [
   {
     "name": "AAAA",
     "time": "today",
     "location": "BBBB",
     "id": 51
   }
 ]

Delete
GET   /(id)

Event.findEvent
id
name
location
time

H2 Database console
http://localhost:8082/
org.h2.Driver
jdbc:h2:./eventsdb;AUTO_SERVER=true

http://h2database.com/html/features.html#auto_mixed_mode

https://addons.mozilla.org/en-US/firefox/addon/rested/
