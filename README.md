mCalendar
=========

A Calendar App builds on top of fullcalendar and Meteor.js




### Start
- Update Packages

		mrt update

- Run Meteor

		meteor run



### API

- Get the loginToken

		curl --data "passowrd=PASSWORD&email=EMAIL" http://localhost:3000/api/login/

- Use your USER_ID and LOGIN_TOKEN to add event

		curl --data "userId=USER_ID&loginToken=LOGIN_TOKEN&title=mCalendar&desc=On Github&start=2014/05/01&end=2014/05/01&allDay=true" http://localhost:3000/api/event/add