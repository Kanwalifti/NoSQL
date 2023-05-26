In this repository, NoSQL using Pymongo analysis is done. Assuming, I am a contracted data analyst for the food magazine Eat Safe, Love, my task was to evaluate the food hygiene ratings data provided by the UK Food Standards Agency. The objective was to assist the magazine's journalists and food critics in determining which establishments to focus on for future articles.

Database and Jupyter Notebook Set Up:

Imported the establishments.json file into MongoDB using the Terminal.
Created a database named "uk_food" and a collection named "establishments" in MongoDB.
Imported the necessary libraries: PyMongo and Pretty Print (pprint).
Created an instance of the Mongo Client.
Verified the creation of the database and loaded data by listing the databases and collections, and displaying one document using find_one and pprint.
Update the Database:

Added a new halal restaurant, "Penang Flavours," to the database with the required information, including the "NewRatingPending" field set to True.
Found the BusinessTypeID for "Restaurant/Cafe/Canteen" and returned the BusinessTypeID and BusinessType fields.
Updated the new restaurant document with the obtained BusinessTypeID.
Checked the number of documents containing the Dover Local Authority and removed those establishments from the database.
Verified the deletion by checking the number of documents again.
Converted the latitude and longitude fields to decimal numbers using update_many.
Converted the RatingValue field to integer numbers using update_many.

