# README

This is my first Ruby on Rails web application. Every aspect of the app was created from scratch(no generators or gems were used besides bcrypt). 
Some functionalities include:
1. Authentication system, users can sign up, log in/out, and edit their profile
2. Users can create new articles and edit their existing articles
3. Users can view all existing articles and all existing users
4. Users can view individual users profiles to see what articles they have created
5. Added restrictions so users can't edit or delete other users profiles and articles
6. Set restrictions so only logged in users have access to certain functions such as creating/editing an article
7. Create categories that each article can be associated with
8. Only admins have the ability to delete users, delete any article, add and edit categories

-- Update views of blog using React
1. Created article component which renders views of articles listing using React
2. Used React to add dynamic update of created at and updated at times
3. Added colorpicker component so users can change the color of the background
4. User color preference is saved so upon login background color is loaded