### Project Title: Recipe Builder

### Project Summary
Our project is meant to help users find recipes given a list of user-given ingredients. This recommendation feature can allow users to choose from a list of generated recipes (selected from a recipe database), that users can sort based on a variety of metrics, including the difficulty of the recipe, # of ingredients, relevance of recipe based on their available ingredients, etc. We also plan on implementing a journal feature where users can write about and journal their cooking experiences after making their recipe.
We hope that this project and website can allow users to easily cook recipes based on ingredients that are already easily accessible in their own fridges, which may decrease the chances of food wastage (as users may be more prone to throw out food ingredients that they don’t use) and we also hope this application will lead to healthier choices, as users would be encouraged to cook their own recipes instead of eating outside, and would also save time, as users could cook recipes from accessible ingredients instead of going outside to buy them.


### Description

When the user types in the ingredients, this app will recommend the possible recipes that can be made with those ingredients. Those recommendations would be sorted and filtered by the user’s preference and also the number of common ingredients with the recipe and the user’s input.  The purpose of this is to reduce the waste of ingredients that users have and give convenience to find the possible recipes instead of searching on Google. 

This app has some creative components that require technical challenges.
The first thing that is cool with this app is this gives a filtering and sorting feature which hugely improves the user experience on searching the recipes. If they cannot filter the resort and the app just shows all of the recipes that have common ingredients with input, that list is too huge and not efficient for the purpose we have which is recommending the best recipes to the user. 
So we will use SQL to filter the database we use according to the user’s choice.

Sorting also gives convenience to the user. When we search for some product it is sometimes hard to find what exactly I want when the list is not sorted as I want. Then I need to scroll down the list for a long time. We want to reduce this inconvenience by giving the option of sorting.
We believe this can be also done with SQL sorting features as we learned in class but the challenging part would be applying multiple sorting aspects when users choose more than one option at once. Then we might need to ask the user to choose the priority of the options and then decide which option should we apply first on ordering. 
### Usefulness

This application is useful because it provides users with a functional and creative way for them to use products that they already have at home. There are simple features such as searching, and filtering, but also more complex features where we can add better UI features and even a record-keeping journal feature where users can input logs of the recipes they created. This journal feature will allow users to create journal entries and save them based on the recipes they want to create entries for. Furthermore, we will include functionality for users to save/favorite/bookmark recipes to look back at later. 

The basic functions of our application allow users to enter the app and input the ingredients they have, and the application recommends a list of recipes that the user could make with the list. Something that makes our application different is that we also incorporate nutritional facts in our recipes. Most websites will only show nutritional information or only show recipes, but we incorporate both in our application to provide ease and convenience to the user by having it all in one place. We also incorporate a journaling system, which makes the application more personal and serves a unique purpose for users to document their experiences with the recipes.	


### Realness

The database we are using: 
(Primary) 
#### Recipe Dataset (over 2M) Foods
2 million recipes, all from baking to French cuisine, and everything in between
Has information of ingredients and directions for the recipes
The data size of 1312871 distinct recipes and 7 columns. The data is in CSV format.
https://www.kaggle.com/datasets/wilmerarltstrmberg/recipe-dataset-over-2m 

(Support) 
#### Nutritional Facts for most common foods
Gives the information about nutrients in the food such as Fat, Carbs, Proteins, etc.
The data size of  329 ingredients dishes and 10 columns. The data is in CSV format.
https://www.kaggle.com/datasets/niharika41298/nutrition-details-for-most-common-foods 



### Functionality 
Our website will provide users to search for recipes by ingredients, which one can sort by difficulty of recipe. 
#### **Filter**
When users try to input the ingredients for recipe search, there would be filters that filter the results based on the number of ingredients, and kind of dish (such as cake, cookie, burger, pasta, etc.). 
#### **Sorting**
When users input the ingredients, the app will give them a list of suggestions for recipes.
Here, we will add a sorting feature.
Users can choose how the list should be sorted, such as more common ingredients with input, less complicated (fewer ingredients needed), less difficult (short direction of recipe), and also the descent of this. 
#### **Modal**
When a user clicks one item in the list, the modal will pop up and give the information about that dish with the ingredients needed and the direction of the recipe. 
Here, we will connect our second database to the major database. 
If the ingredient of that dish exists in the second database, then the modal will give the information about the nutrition of each ingredient. 


### A low-fidelity UI mockup: 


![UI Mockup](https://github.com/AnaghaTiwari/anaghatiwari/blob/20180a7be2a1e4c22ff7eb072179013f8da0eeb8/Drawing.sketchpad.png)



### Project work distribution: 
<img width="571" alt="image" src="https://github.com/cs411-alawini/sp24-cs411-team035-dass/assets/62567659/20a83e43-55bb-4f77-a641-7bc31c8f97f9">
