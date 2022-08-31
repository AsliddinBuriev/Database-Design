Database Design
This post will teach relational database design by building a photo-sharing app.

The database of the app we are building will contain 4 different tables as shown (graph 1.1) and the tables will be related to each other. Now, we have a couple of questions in our minds.
First, why or when do we create new tables?
When the application we are building has distinct resources such as users, products, comments, etc.
When the resource has the potential to grow indefinitely.
Now, we know that our application has 4 different resources and each of them may increase indefinitely.

Second, how do we set up the relationship between these tables?
Before answering this question, let’s learn some types of relationships that might exist between the tables.
