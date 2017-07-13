# Aggy
Meeting Bot for agile and self managing teams

This might be a single page application to help plan, run and document meetings.

- Users can log on via google, add up to 10 'concerns' for the agenda with priority order.
- Users can see other users concerns and add then to their own list.
- The system groups similar items via matching words.
- At start of meeting a prioritised agenda is produced.
- The system allocates equal time to each item
- at the end of the time box aggy asks for outcomes and 'Actioner' (one of the users)
- At the end of meeting it produces minutes document and emails it to all attendees / posts it to relevant slack channel.

Frontend - Elm:

http://courses.knowthen.com/p/elm-for-beginners

Backend - [Postgrest](https://postgrest.com) and [postgres](https://postgresapp.com/)


example repo using same stack: https://github.com/diogob/elm-workshop

examples using query builder: https://github.com/john-kelly/elm-postgrest/tree/master/examples
