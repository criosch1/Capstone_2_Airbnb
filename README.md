![alt text](https://www.esquireme.com/public/images/2019/11/03/airbnb-678x381.jpg)

# Paradise Lost? The Commercialization of Airbnb in Crete, Greece.

## Blog Version


# Summary
My name is Christian Rios-Chambi and I am a Data Analyst consultant working for the Greek government. I have been contracted to analyze the spread of foreign commercial Airbnb hosts and their listings in Crete, Greece. 

## How Airbnb works
Airbnb, Inc. is an American vacation rental online marketplace company based in San Francisco, California, United States. Airbnb offers arrangements for lodging, primarily homestays, or tourism experiences. Airbnb claims to be part of the "sharing economy" and disrupting the hotel industry. However, data shows that the majority of Airbnb listings in most cities are entire homes, many of which are rented all year round - disrupting housing and communities.


## The Dataset 
The data used was from the Inside Airbnb website. The data behind the Inside Airbnb site is sourced from publicly available information from the Airbnb site. The data has been analyzed, cleansed, and aggregated where appropriate to facilitate public discussion.

## **Main Points**
- **How many foreign hosts are in the Crete Airbnb marketplace?**
- **How many foreign listings are in the Crete Airbnb marketplace?**
- **What's the growth rate for both?**


# Project Steps & Further Questions:

## Data Cleaning:

- Remove duplicates or records with missing or mismatched values.
- Removing unnecessary columns. 
- Replacing certain null values with appropriate zero values.

## Data Wrangling:

- Created new columns for better analysis.
- Creating functions to help label data.
- Creating Visualizations.

## How many foreign commercial hosts are in the Crete Airbnb marketplace?:
- Created a metric to differentiate between foreign commercial and non-commercial hosts.
  - Host has to have more than 1 listing.
  - Listing is available for more than 60 days out of the year.
  - Host location is outside of Greece.
- Used the first review date to estimate the date the property went live.
  - Needed in order to calculate the growth over time.
- As of May 2019, there are 668 foreign commercial hosts and 2,360 Greek commercial hosts.
  - A 1:4 ratio is observed. 
- Foreign commercial hosts increased at an average of 124%, Greek commercial hosts increased at an average of 169%. 

## How many foreign listings are in the Crete Airbnb marketplace?:
- Used the same metric as above, but now focusing on the listings.
- As of May 2019, there are 1,299 foreign commercial listings and 8,960 Greek commercial listings.
  - a 1:7 ratio is observed.
- Foreign commercial listing increased at an average of 51%, Greek commercial listings increased at an average of 57%.
 
## Recommendations and Next Steps:
- Although foreign commercial hosts have been increasing over time, greek commercial hosts outpace its growth by 45%.
- Foreign commercial listings are also increasing over time, but just like our analysis for hosts, Greek commercial listings outpace foreign commercial listings.
- Greater government oversight needed for Airbnb.
- Limit the amount of Airbnb listings per person.


# Contact Information 
- **Name:** Christian Rios-Chambi
- **Email:** crioschambi@gmail.com
- **LinkedIn:** linkedin.com/in/christian-rios-chambi/
- **Github:** github.com/criosch1
