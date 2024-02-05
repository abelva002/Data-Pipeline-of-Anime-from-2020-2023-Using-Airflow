## Problems Encountered

1. Unable to install Selenium on the container / on Docker. Although I have created web scraping python script for scraping data as well as cleaning and organizing the data, I could not use the script as I was unable to install Selenium on Docker. Despite testing many alternative and trying to see different approach, I have not managed to make it work. After spending some amount of time without a solution and also because of lack of time I decided to abandon it and use the API approach.
   
2. It's more about a dillema rather than problem but I don't include the Postgres connection credentials on docker-compose file as well as other file like .env and stuff because of security concerns. I realized that some others did but I was unsure if I should because whether it is using .env or in docker-compose, if you upload the credentials to github it will be visible anyway so I am still not sure if I should do it.

3. This one is also less of a problem and more of explanation of some things noted / nitpicks during the presentation. About usage of while, it's just the first thing that comes to mind and after testing times and times again I just don't think that there are issue in the usage, but as noted I will try to reduce the usage of it in the future. About storing drop_list, or any list which has many members, on other file is also noted for future reference. And lastly, for the naming of the database (jikan_myanimelist_2020) and not including 2023 is because at first I only intended for it to be used for testing but I ended up just creating a whole dashboard while testing. That is why I stick with the name instead of changing it, to prevent having to make the connection again because if you change name you (technically) have to connect to a different database (with the new name).

## Improvement for the (theoretical) Next

1. Add more analysis based on the data already on the DB. For example, top anime within genres, genres statistics done by studios, and many more.

2. Implement Machine Learning models to further analyze the data, for example using clustering to see groups of anime clustered together based on information available in the DB. 
