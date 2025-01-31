# Vinted-Scraper
This is a tool to download images and scrape data from Vinted & Depop and store it in a SQLite database.

## How to use
### Vinted
Put the user IDs of the accounts in the users.txt and run the script.
The script will download all the images and put it in the downloads folder.
The data will be stored in the SQLite database.

### Depop
Put the usernames of the accounts in the users.txt and run the script with `-d`.
The script will download all the images and put it in the downloads folder.
The data will be stored in the SQLite database.

## Data that will be scraped
All the images of the products of the users will be downloaded. The avatar of the user will also be downloaded.

All the info will be stored in the sqlite db in the following tables:

### Vinted Users
 `Username`  
 `User_id`     
 `Gender`  
 `Given_item_count`  
 `Taken_item_count`  
 `Followers_count`  
 `Following_count`  
 `Positive_feedback_count`  
 `Negative_feedback_count`  
 `Feedback_reputation`  
 `Avatar`  
 `Created_at`  
 `Last_loged_on_ts`  
 `City_id`  
 `City`  
 `Country_title`  
 `Verification_email`   
 `Verification_facebook`  
 `Verification_google`  
 `Verification_phone`   

### Vinted Products
 `ID`  
 `User_id`     
 `Gender`  
 `Category`           
 `Size`         
 `State`  
 `Brand`  
 `Colors`  
 `Price`  
 `Images`  
 `Description`  
 `Title`  
 `Platform`  
 
 ### Depop Users
 `Username`  
 `User_id`     
 `Bio`  
 `first_name`  
 `followers`  
 `following`  
 `initials`  
 `items_sold`  
 `last_name`  
 `last_seen`  
 `Avatar`  
 `reviews_rating`  
 `reviews_total`  
 `verified`  
 `website`  
 ### Depop Products
 `ID`  
 `Sold`    
 `User_id`    
 `Gender`  
 `Category`           
 `Size`         
 `State`  
 `Brand`  
 `Colors`  
 `Price`  
 `Images`  
 `Description`  
 `Title`  
 `Platform`  
 
 If you have any feature requests don't hesitate to open a issue :)
