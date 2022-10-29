![open-rental_banner](./Openrental.png "open-rental")

### Open Rental is a repository for storing data regarding rental houses and PGs. Its completely open source and highly explainable with the details from past and present tenants. Not from the owners.

# Getting Data:

## 1\. Fully Furnished:

| Action | Query String |
| --- | --- |
| All data | https://api.gitrows.com/@github/rayofreflection/open-rental/fully-furnished/data.json |
| Particular value | https://api.gitrows.com/@github/rayofreflection/open-rental/fully-furnished/data.json?area=navalur |
| Numeric search | https://api.gitrows.com/@github/rayofreflection/open-rental/fully-furnished/data.json?advance=lt:7000 |

## Note:

### Numeric search:

|  Parameter   |   Operation  |
| --- | --- |
| lt  | less than |
| gt  | greater than |
| lte | less than equal |
| gte | greater than equal |

## Format :

```JSON
{
    "name": "Revanth",
    "contact": {
      "email": "communication@rayofreflection.org", 
      "linkedin": "https://www.linkedin.com/in/revantharunachalam/",
      "instagram": "https://www.instagram.com/rayof_reflection/"
    },
    "area": "navalur", 
    "city": "chennai", 
    "location": "https://goo.gl/maps/VSSbDk3uum5RABKk6",
    "rent": 6000, 
    "advance": 5000,
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
