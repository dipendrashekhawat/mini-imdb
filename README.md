# mini-imdb

Create a IMDB.com like website with basic CRUD and movie listing using C# (Asp.NET MVC / Asp.NET Core). 

The application would have the following entities:

| Actors  | Movies  | Producers |
| ------- | ------- | --------- |
| Name | Name | Name   |
| Gender | Year of Release | Gender   |
| DOB | Plot | DOB   |
| Bio | Poster(image) | Bio   |

### Relationships
<ol>
<li>Actor can act in multiple movies</li>
<li>Movie can have multiple actors</li>
<li>Movie has only one producer</li>
<li>Producer can produce multiple movies</li>
</ol>

### Application specifics (minimum requirements)
1. Screen to list all movies with Name, Year of release, Producer and all Actors of that movie
2. Screen to ‘add’ a new movie with the necessary fields with existing actors and producers. If the user
wants to add new ‘Actors’ and ‘Producers’ while creating the movie which are not present in the
database then he should be able to do so while being on the same screen.
3. ‘Listing’ screen should allow user to click on ‘Edit’ and edit all the details of the movie and save it
would be a nice to do thing.

### Hints and Tips
1. Focus on database design (Normal Forms).
2. Best practices. Design/Styling/CSS is not critical; functionality is.
3. Define rules for validation.
4. Use of upcoming JS frameworks like Vue/React
5. Use Docker / ASP.NET Core./Web API

**change from temp branch and fork


