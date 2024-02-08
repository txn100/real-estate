# Swiss Real Estate Data




This is not the scraper, but the scraped data. If you want to see the scraper's repo follow this link : https://github.com/sapg-dev/Swiss-Real-Estate-Scraper/tree/master


## Dataset Description 
This repository hosts JSON-formatted data extracted from a major Swiss real estate website. It includes comprehensive listings for both buying and renting properties across all Swiss cantons.

## Data Format
Each JSON object in the dataset represents a single property listing with the following structure:

```json
{
    "price": Integer,
    "addresses": [String],
    "description": String,
    "elements": [String],
    "url": [String],
    "link1": String,
    "link2": String or null
}
