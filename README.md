# Goals：
This project is to preliminarily practice the ability to use and apply SQL concepts to complete tasks in real scenes。

### Relational Schema：
User [id, fName, mInitial, lName, age, phone, email, nationality, significantOther]
Event [title, date, description, location, sponsor]
Attends [id, title, date, travelMethod]
Friends [requestor, requestee, startDate

### Foreign Keys

User.significantOther references User.id
Attends.{title, date} references Event.{title, date}
Attends.id references User.id
Friends.requestor references User.id
Friends.requestee references User.id

Use the LIMIT 10 clause to only capture the first 10 tuples of the table.
