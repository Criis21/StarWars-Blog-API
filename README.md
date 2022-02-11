<p align="center">
	<img
		width="300"
		alt="4Geeks Academy"
		src="https://github.com/4GeeksAcademy/About-4Geeks-Academy/blob/master/site/static/background_art.jpg?raw=true">
</p>


<h1 align="center">Welcome to 4Geeks Academy</h1>


<h3 align="center">&lt;StarWars Blog API&gt;</h3>

## Content

1. Language
2. Project instructions
3. Extra


## 👩‍💻Language

<p>This project contains:</p>

<ol>
    <li>Rest</li>
    <li>Flask</li>
</ol>

## 📝Proyect instructions

Create an API that connects to a database and implements the following Endpoints (very similar to SWAPI.dev or SWAPI.tech):

[GET] /people Get a list of all the people in the database
[GET] /people/<int:people_id> Get a one single people information
[GET] /planets Get a list of all the planets in the database
[GET] /planets/<int:planet_id> Get one single planet information
Aditionally create the following endpoints to allow your StartWars blog to have users and favories:

[GET] /users Get a list of all the blog post users
[GET] /users/favorites Get all the favorites that belong to the current user.
[POST] /favorite/planet/<int:planet_id> Add a new favorite planet to the current user with the planet id = planet_id.
[POST] /favorite/people/<int:planet_id> Add a new favorite people to the current user with the people id = people_id.
[DELETE] /favorite/planet/<int:planet_id> Delete favorite planet with the id = planet_id.
[DELETE] /favorite/people/<int:people_id> Delete favorite people with the id = people_id.
Your current API does not have an authentication system (yet), that is why the only way to create users is directly on the database using the flask admin.

## 😎 Extra

Feeling confident?
The following requirements are not necesary to successfully complete this project, but you want try coding them if you feel like challenging yourself ☺️

+1 Create also an enpoint to add (POST), update (PUT), and delete (DELETE) planets and people, that way all the database information can be manage using the API instead of having to rely on the flask admin to create the plantes and people.
