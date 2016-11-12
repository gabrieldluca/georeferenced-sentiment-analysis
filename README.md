![img](https://cloud.githubusercontent.com/assets/22268489/20234697/4e21fcfa-a867-11e6-9027-87691a234431.png)
# Twitter Trends
This project develops a geographic visualization of twitter data across the USA. Main characteristics include dictionaries, lists, and data abstraction techniques to create a modular program. 

The map displayed above depicts how the people in different states feel about Beyoncé. This image is generated by:

- Collecting public Twitter posts (tweets) that have been tagged with geographic locations and filtering for those that contain the "texas" query term,
- Assigning a sentiment (positive or negative) to each tweet, based on all of the words it contains,
- Aggregating tweets by the state with the closest geographic center, and finally
- Coloring each state according to the aggregate sentiment of its tweets. Red means positive sentiment; blue means negative.

The complete description of the project can be found in `project.pdf` file.

**Special acknowledgment:** Aditi Muralidharan, who developed this project with John DeNero; Hamilton Nguyen, who extended it; Fernando Castor, who parcially translated the specification to brazilian portuguese. 