# finalproject


DAY 1:

On the first day when I got acquainted with the project, I started to create the project plan. I immediately started with the description of the project together with its main objectives that follows :

   Project Descriptions
Skill-Matrix is a project where the main goal is to collect data from the survey. This survey will contain many questions for a large amount of users in different timestamps. The questions will be displayed in different types.

   Project Requirements  
-The project must meet the list of requirements to achieve success.
-Improve the user experience.
-Performing end user functionality analysis, current web review and information architecture design.
-Full site testing to minimize any possible error.

I would say it was not that hard creating a project plan for me because before have studied project management.

As i helped my colleges with project objectives and requirements my next task was the database of the project.

On day one i worked with dbdiagram.io because i wanted to learn more about the relations between the tables.
Then I designed a main line of the database that could later be changed depending on the project.

Later then I created all the tables for the database based on the example Marco sent us.I worked on Adminer (8008) and i wrote the line of the tables on the SQL command.After the tables was succesfully created on the adminer i went to Hasura on port (8080) and started migration of the tables.
After all the migration status was up and succesful i planted the dummy data on hasura/migration seeds folder.
Some of the commands ==> make migrate-status , make migrate-up steps=X . make migrate-down steps=X , make migrate-create name=XXXXX , make seed.



DAY 2:  

In the day 2 there was a lot of issues with types of variables .The types of the variables didn't correspond with the large amount of data that the app is going to collect.
As i changed a lot of columns in different tables at up.sql and down.sql files ,I commit the changes.The commands that were used to achive that were :
make migrate-down steps=x , make migrate-up step=x and make seed.

Every table : users, board, survey, questins and asnswers was filled out with dummy data.I also had some issuees with the type of the variables that didn't had the default value determined.I make sure that every table had her own primary and foreign key to have relations between them and that i could track the tables on hasura and confirm the dummy data.



DAY 3:

Day 3 was really difficult for me because i couldn't create actions on hasura.I tried a lot of different ways to create it but i got different errors.The actions on hasura could later be used as API session to connect the backend with frontend.

The first error i dealt with was “status:500”.The database didnt have a connection.By the help of our seniour colleges I later fixed that error but still i got another error about webhook handler.As i searched a lot in stack overflow and different source i couldnt fix that.Even after our senior colleges help me fixing this error the connection with the database wasn't succesful.Together with my team i started looking for other solutions because me and my partners colud't create a succesful action on hasura.
Another thing i should mention was the database.I did different changes to the tables of the database.Many variables required different data types as the project goes by.I fixed those and commit the changes.


DAY 4:

As I couldn't fix a sucessful connection with the database day 3 can be counted as a total failure.
Me and my colleges were focues on the graphql and backend part later then as we dealt with many errors we changed strategy and they started creating a new question.js page were the answers data table later gone be fetched.
I finally fetched data from the database by creating a simple query on questions.js with the corresponding data.I used map function to get the answers data one by one.This wasnt possible with the help of our senior colleges.

I faced different errors with when fetching the data because when i checked the console data where succesfully fetched but were undefined.Another type of error happened when i forgot to toggle all the permisions on hasura.Later on as i searched on google i found out that you can save the permissions by : hasura metadata export.Another problem me and my colleges dealt with was writting 2 querys on one component.I finally fetched a list of questions to the frontend with get method.



