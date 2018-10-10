# Shopping-Cart-App-Blog-Post


This project features a RESTful MVC Framework with Devise for Users authentication and Products with CRUD functionality.

Here I have a brief walkthrough of the (Web App)[https://github.com/AndrewKairys/Shopping-Cart]

The process was straightforward in that I had a goal for a user to be able to add products to a communal market space. They would store their products and associated information. Upon a user being added to the database there is a form input field that ties into a daily_calories column in my sqlite3 database. I was then able to use erb to expose the user's daily_calories, then subtract the the total value of the column calories on the meals table. I used the ActiveRecord::Calculations methods pluck and sum to accomplish this. I also implemented a delete route that handles the Delete All button on my meals page tby destroying each meal object through the has_many/belongs_to relationship that was set up in the models of my framework.
