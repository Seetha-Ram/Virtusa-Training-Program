# Virtusa-Training-Program
How to create a food recipe app using ReactJS ?
We are going to make a food recipe app using React.js.

Pre-requisite:
React hooks
React components
JavaScript ES6
API 
CSS
Approach: Here in this app we should have a component where we are going to show our food recipes. And we need to fetch all the required food recipes using a food recipe API. We will fetch the API data, store those data in a component structure using react hooks (useEffect, useState ).

Getting food recipe API KEY: First of all we will get all the food recipes by fetching the data from API.  For this, we will use the  platform called EDAMAM.  (  https://developer.edamam.com/ )

First we need to signup and  then go to the APIs section in the navbar.
Click start now in the Developer section.
Then go the Dashboard section(top right)>click Application>in the left side
There’s a Recipe Search API option > click view on that section
From there copy your Application ID and Application Keys and store it somewhere.
Creating the react app and installing all the required packages:

Step 1: Create a React application using the following command:

npx create-react-app foldername
Step 2: After creating your project folder i.e. foldername, move to it using the following command:

cd foldername
Project Structure: It will look like the following.



Step 3: Now inside src/App.js file, provide tour own app id and app key in the place of <YOUR_APP_ID> and <YOUR_APP_KEY> which you have got from EDAMAM.


Step 4: Make a component file in the src folder named “Recipe.js”(You can name it with whatever you wish to) which is imported in App.js. Edit src/Recipe.js file. This file contains the whole structure for recipe cards.

Step 5: Now add styling inside src/App.css.

Step 6: Create a new file called “recipe.module.css” in src folder. This file is for adding style to  src/Recipe.js file.

npm run start Output: You will see the following output on your browser screen.
