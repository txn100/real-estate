# Swiss Real Estate Data




This is not the scraper, but the scraped data. If you want to see the scraper's repo follow this link : https://github.com/sapg-dev/Swiss-Real-Estate-Scraper/tree/master


## Dataset Description 
This repository hosts JSON-formatted data extracted from a major Swiss real estate website. It includes comprehensive listings for both buying and renting properties across all Swiss cantons.

## Data Format
Each JSON object in the dataset represents a single property listing with the following structure:

```json
{
    "price": 100,000,000,
    "addresses": "1 Real Swiss Address Trust,
    "description": "Really really big house, with nice view on construction" ,
    "elements": "Communal garden to share with residents", "Natural swimming pool naturally cleaned by algae and tadpoles",
    "url": estate.com/nicepic.png, array of urls of all pictures, not downloading for storage reasons
    "link1": String
    "link2": String or null // original announcer
}
