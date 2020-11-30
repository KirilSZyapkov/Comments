# Comments

Write a function that stores information about users and their comments in a website. You have to store the users, the comments as an object with title and content and the article that comment is about. The user can only comment, when he is on the list of users and the article is in the list of articles. The input comes as array of strings. The strings will be in format: 
"user {username}" – add the user to the list of users 
"article {article name}" – add the article to the article list 
"{username} posts on {article name}: {comment title}, {comment content}" – save the info 

At the end sort the articles by count of comments and print the users with their comments ordered by usernames in ascending. 

Print the result in the following format: 
"Comments on {article1 name}: 
--- From user {username1}: {comment title} - {comment content} 
--- From user {username2}: … 
Comments on {article2 name}: 
…" 
