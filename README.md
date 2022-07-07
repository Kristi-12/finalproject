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



DAY 2:  


After task day 1 to start up the p'roject, in the day 2(two) we located a lot of issues with types of variables .This was a big problem for us because the types of the variables didn't correspond with the   large amount of data that the app is going to collect.
 Our main focus was dealing with types of variables and after finishing, our main thoughts was to prepare the dummy data in seed table. 


 2.The seed's table is created in base of the tables we was created before for users, board, survey, questins and asnswers. Inserting data had an issue that the type of the variables didn't had the default value. Every table has her own primary and foreign key to have relations betwwen them and the data was succesfully applied on HASURA.
