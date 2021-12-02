---
title: "Collaborative Cookbook"
date: 2021-09-14
---
# Collaborative Cookbooks

When I moved out of my house, the majority of my dinners were sourced through Skip The Dishes and Uber Eats. The effects of repeatedly eating processed food and the cheap oils used in restaurants didn't show for two years. Once I moved back home, I decided to get back into shape, so I took some time to read up on various parts of the cooking process and filled my pantry with healthy cooking oils and nutritious ingredients. Being a vegetarian and having eaten my mom's Indian cooking all my life, I continued the tradition and started making dal and curry at home. Learning my mom's recipes seemed a daunting task at first as she would tell me all kinds of tricks to get the most out of the ingredients and rattle off the recipe quickly but putting it into practice was not too bad. The hardest part was just cutting the vegetables.

My mom is a great cook. She's built up a repertoire of tips and tricks for fixing issues that come up as well as spices and herbs that can work as alternatives to what's in the recipe. All this information can be found online too. Blogposts with recipes will sometimes give helpful information in this regard, but the information is scarce and hidden behind a lot of fluff. Once I read enough information about the different cooking methods and how to make a variety of dishes, I found I could modularize each part of the cooking process. I found that when cooking a meal, each ingredient goes through a pipeline of methods and the combination of ingredients used varies by the method used to cook.

This realization gave me the idea of creating a visual cookbook that dynamically provides users options on ingredients and methods to use when creating a recipe. In creating this application, I am testing two hypotheses. The first is that modularizing a recipe will allow users to work together when creating a recipe as well as make it easier to copy and alter recipes when adding them to a personal database. The second theory I am testing with this application is that creating modular recipes is more intuitive when thought of as graphs with nodes and directional edges that show the flow of the recipe. The graph visually transfers information of the methods used which can be drilled into to view the ingredients used and further into preparation instruction for each ingredient. Aditionally, we can alter the view of the graph to various other visual representation methods such as: GANTT charts for complex meal planning, pie charts for nutrition planning, or plain text for traditional reading.

To test these theories, I am currently working on a project that allows people to collaboratively create personal cookbooks and share it online. The process will work like GitHub’s forking and branching methodology and allow users to fork others' recipes and make their own alterations. A graph database solution will allow the application to be feature rich with information including nutrition information, alternative ingredients, and tips and tricks specific to ingredients, methods, and steps. The advantage is that all this information travels with the ingredient or cooking method and can be hidden until pertinent or required by the user.

What excites me about this project is the variety of ways a graph database of recipes can create solutions to a variety of problems and work with various applications and products such as: an IoT cookbook for the kitchen that provides a simulation of the cooking process as the user cooks; a central search feature for information regarding various recipes, nutrition value, and preparation instructions; and users can create novel dishes that can combine any variety of styles around the world and the logic of the graph will ensure that all the ingredients are cooked correctly. I hope to bring this app to young adults who would like to bring traditional cooking methods into their lifestyle and collaborate with family and start cooking delicious meals at home. My vision is to simplify the cooking process using a graph network with high fidelity such that the application transfers all necessary information needed to make a great meal.