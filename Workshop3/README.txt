Into this analisys that I've made about the database that we got directly from the webpage of IMB, 
I checked directly inside of the page the informaiton that the program were getting With this 
I noticed that normally the program generate a dataframes of movies of 720 movioes in total,
 all of them with the directly information of the full title of the movie in the spanish languaje, 
also it get the year of release and the common genres in where the movie have been clasified, 
added to this the dataframe get the information of all the principal actors, with this information
 I decided to order the questions to filtrate the program, these are the questions and the order that I'll be using onto my program

Which movie gender do you want to see? This will help me in order to filtrate between the different movie genders that we have,
 reducing the amount of movies that the system can recommend, for example into the first try that I've made in order to filter the movies,
 I try to check the movies that have the "Drama" genre on them, this have reduced the amount of movies from 702 to 316, almost the half of the movies where filtrated for not having the selected genre on them


2.which release year do you want to see in your movie?
After I filtrate the amount of movies based on the genre, the best option that I got to continue filtering them were the year in where the movie were released, 
this because as we know the year of a movie can decide the amount of special efects that can be on it, the production that were made, or also even the plot of the movie, for example the movies of the "Terror"
 genre on the years previous of 2000 were made as slasher movies, while the released after that year, are more enfocated into Psychological suspense But when I were making the process of the code, 
I noticed that the program only have the option to get movies between 2023 and 2025,
 that's why I needed to make an conditional to check that the answer to the movie will be one of the available years (with my example of bellow this reduced the filter from 316 to 60 movies

Do you have a prefered actor that you want to see into the movie? Which one?
As I have already filtered the 3/4 part of the movies I want to reduce the amount to the minimal amount of movies possible, 
what I've done with the quesiton of the actor is found a selected parameter that will no completely repeated on the movies, something that will be specific just for a certainly amount of them, 
on my example I checked with the actor Robert Pattinson, and I reduced the amount of movies from 60 to 4

