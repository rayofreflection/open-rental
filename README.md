![open-rental_banner](./Openrental.png "open-rental")

### Open Rental is a repository for storing data regarding rental houses and PGs. Its completely open source and highly explainable with the details from past and present tenants. Not from the owners.

### Getting Data:

1\. [Fully Furnished](https://api.gitrows.com/@github/rayofreflection/open-rental/fully-furnished/data.json)

### Format :

```JSON
{
    "name": "Revanth",
    "contact": {
      "email": "communication@rayofreflection.org", 
      "linkedin": "https://www.linkedin.com/in/revantharunachalam/"   
    },
    "address": {
      "place": "Olympia Opaline", 
      "landmark": "Opposite of Vivira mall", 
      "area": "Navalur", 
      "city": "Chennai", 
      "location": "https://goo.gl/maps/VSSbDk3uum5RABKk6"
    },
    "payment": {
      "rent": 6000, 
      "advance": 10000
    },
    "sharing": "Single", 
    "parking": true, 
    "parking_type": "open roof",
    "notice_period_in_months": 3,
    "staying_at_present": true, 
    "agreement": true, 
    "privacy": true,
    "separate_eb_meter": true,
    "appliances": {
      "common": ["Water heater", "Water purifier", "Television", "Amazon fire TV stick", "Shoe rack", "Washing machine"], 
      "individual": ["Bed", "AC", "Table", "Shelf"]
    }
}
```
