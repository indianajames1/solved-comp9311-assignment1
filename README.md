Download Link: https://assignmentchef.com/product/solved-comp9311-assignment1
<br>
A music organization hires you to design a small database to store information about the creation and publication of songs. You’re given the following requirements:

<ul>

 <li>A song is identified by song ID. For each song, we want to record its title and genres. A song may have multiple genres.</li>

 <li>An artist is identified by his/her artist ID and we also record his/her name, birth date, and contact number. A song must be created by one or more artists and an artist must have created at least one song. We also want to record the role (e.g. writer, producer) when an artist participates in the creation of a song.</li>

 <li>A company is identified by its company ID, and we also need to know its name and address. The address is composed of street and suburb. An artist may join multiple companies and a company must have at least one artist. Some artists may not join any companies. The number of artists in a company is needed.</li>

 <li>An album is uniquely identified by its album ID, and we also need to know its name. An album must have one or more songs. A song must belong to exactly one album. We also want to know the number of songs in an album. For each album, we record the company which publishes it. A company may publish zero or more albums and an album must be published by exactly one company. We also want to record the publish date of an album. Draw an ER diagram to represent this scenario, and clearly state the assumptions you make if any.</li>

</ul>




<strong>Question 2 </strong>

Convert your ER-diagram from Question 1 into a relational model.

<h2>Question 3</h2>

Consider the following relational schemas:

Movie (<u>mID</u>, title, runningTime, releaseDate)

Cinema (<u>cID</u>, cName, location)

MovieShowing (<u>mID, cID</u>, sDate, eDate)

Customer (<u>cusID</u>, name, age, gender)

WatchMoive (<u>cusID, mID, cID</u>, date)

Director (<u>dID</u>, name, age, gender)

Filming (<u>dID, mID</u>)

GenreOfFilm (<u>mID, genre</u>)




Write relational algebra expression to answer the following questions:

<ul>

 <li>Find the titles of ‘comedy’ movies that are shown in the ‘Event’ cinema at ‘George St’.</li>

 <li>Find the titles and release dates of movies that are shown in both the ‘Event’ cinema at ‘Chatswood’ and the ‘Hoyts’ cinema at ‘Chatswood’.</li>

 <li>Find the names of ‘male’ customers who have watched the movie ‘Aquaman’ directed by ‘James Wan’ and have not watched any other movies directed by him.</li>

 <li>Find the names of directors who have been to a cinema to watch a ‘fantasy’ and ‘violence’ movie directed by himself.</li>

 <li>Find the names of the customers aged between ‘30’ and ‘50’ who have watched all the films whose running time is longer than ‘120’ minutes and have never been to any ‘Hoyts’ cinema.</li>

</ul>




Note that, only the following operators can be used in your answer: <em>Select</em>, <em>Project</em>, <em>Union</em>, <em>Intersection</em>, <em>Difference</em>, <em>Cartesian Product</em>, <em>Join</em>, and <em>Divide</em>. The running time of a movie is counted in minutes. To simplify the questions, each person’s name is unique. So, if a customer’s name is the same as a director’s name, you can regard them as the same person.





