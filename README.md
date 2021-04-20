# Garcia_Ngau_Zomato_SQL

## Objective:

The goal of this project is to restructure a flattened dataset, and load into a SQL database. We also demonstrated some analysis to demonstrate the convenience to have this dataset stored in a database.

## Project
 Selected from the project ideas listed in the "Final Project Description" document posted under the blackboard "Assignments" section
 Zomato Restaurants: https://www.kaggle.com/shrutimehta/zomato-restaurants-data
 
## Approach
We worked with Zomato dataset that is stored in Kaggle commnunity. https://www.kaggle.com/shrutimehta/zomato-restaurants-data

Zomato is a project launched in Delhi 12 years ago, and is present in 10000+ cities globally. Zomato is one of the 'largest food aggregators in the world' and their mission is to connect people to food.(https://www.zomato.com/who-we-are)

![image](https://user-images.githubusercontent.com/54993787/115320794-840f8f80-a150-11eb-878e-52b8abbe304c.png)

First, the dataset was collected from the Zomato API in the form of .json files (raw data) and sotred in the Comma Separated Value file Zomato.csv. We explored this dataset by visualizing the information that has been fetched, and have a better understanding of the dataset. 

Every Restaurant contains:
- Restaurant ID: unique ID.    - Average cost for two: Different currencies    - Rating color
- Restaurant Name              - Currency: Currency of the country             - Rating text
- Country Code                 - Has table booking: yes/no                     - Votes
- City                         - Has Online delivery: yes/no
- Address                      - Is delivering now: yes/no
- Locality verbose:            - Switch to order menu: yes/no
   Detailed description of the locality
- Longitude                    - Prince range
- Latitude                     - Aggregate Rating: Average rating out of 5
- Cuisines:                    
   A list of the cuisines offered by the restaurant.








would like to work on the dataset that we will download from Kaggle. We will then use python to do exploratory data analysis on the dataset to see the type and distribution of each variable. Since we are working in a group, we would like to complete our python code on the Google Colab environment so that both of us can change or add stuff at the same time. 
Once we have a better understanding of the dataset, we plan to build an entity-relationship model to design the architecture of the database. This will allow us to have a clear vision of our database 
Then we will build and distribute the different tables by using the pyMySQL environment. 
One analysis we expect to work on is to visualize the data based on their location, cuisine, price, and ratings. The final goal would be to provide an efficient and easier way for end-users to search for specific information.  
