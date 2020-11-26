# SimpleGoServer

![goLogo](/goImage.png)

A simple webservice implemented in Go. Used to learn Golang.

To compile into exe, navigate to the folder and run:<br>
```bash
go build .
```
A user is defined by the following fields:<br>
* ID
* FirstName
* LastName

Methods include:
* GET: returns a list of users
* POST: to add user
* PUT: to update an existing user
* DELETE: to remove a user
