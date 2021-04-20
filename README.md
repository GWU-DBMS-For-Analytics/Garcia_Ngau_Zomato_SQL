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
- Restaurant ID: unique ID.        
- Restaurant Name                            
- Country Code                                      
- City                          
- Address                       
- Locality verbose: Detailed description of the locality
- Longitude                     
- Latitude                     
- Cuisines: A list of the cuisines offered by the restaurant.
- Average cost for two: Different currencies
- Currency: Currency of the country
- Has table booking: yes/no
- Has Online delivery: yes/no
- Is delivering now: yes/no
- Switch to order menu: yes/no
- Prince range
- Aggregate Rating: Average rating out of 5
- Rating color
- Rating text
- Votes


Once we have a better understanding of the dataset, we plan to build an entity-relationship model to design the architecture of the database. This will allow us to have a clear vision of our database 
Then we will build and distribute the different tables by using the pyMySQL environment. 
One analysis we expect to work on is to visualize the data based on their location, cuisine, price, and ratings. The final goal would be to provide an efficient and easier way for end-users to search for specific information.  
