# Garcia_Ngau_Zomato_SQL

### Contributors:
- Jose Garcia:
- Kahang Ngau: 

## Objective:

The goal of this project is to restructure a flattened dataset, and load into a SQL database. We also demonstrated some analysis to demonstrate the convenience to have this dataset stored in a database. Additionally, to provide an efficient and easier way for end-users to search for specific information.  
 
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

Then we created in MySQL our database to store the different variables from the database and created relations between the tables by the Restaurant_ID key. 
![image](https://github.com/GWU-DBMS-For-Analytics/Garcia_Ngau_Zomato_SQL/blob/main/Img/SchemaDB.png)


