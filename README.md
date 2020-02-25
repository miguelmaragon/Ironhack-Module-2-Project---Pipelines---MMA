# Ironhack-Module-2-Project---Pipelines---MMA

Description

The project consists of making a visualization of the most striking data of the Airbnb apartments in New York.

The main objective is to reduce the existing apartments in New York, according to:
	- A large number of reviews.
	- A large average number of reviews during the month.
	- Low annual availability, since understanding that it is a good apartment will be better because many people want it.
	- A reasonably low price.
	- The most important thing is that the apartments are close to the points of interest for tourists. 


Data used
The Airbnb apartments have been obtained from the following database:
https://www.kaggle.com/dgomonov/new-york-city-airbnb-open-data

The New York sites of interest have been obtained from the following link: 
https://mygeodata.cloud/data/download/osm/tourist-attractions/united-states-of-america--new-york/new-york-county

Development

In the first part, we wanted to analyze the number of apartments distributed in the four most important neighborhoods of New York and by the type of room.
Additionally, the total number of reviews received by room type and the total number of rooms by room type.

From the first part, we can see the great existing offer, so we wanted to analyze under the criteria of the description the best apartments in 1 km of Times Square.
Therefore, we wanted to superimpose the two maps of apartments and points of interest. The most complex has been precisely this. 
It has been solved by including the two files in the same database, making the latitudes and longitudes coincide. Additionally, a new field has been included to detect if it is an apartment or a place of interest.
Finally, it is represented on a map and, as an example, the best apartments within a radius of 1 km from Times Square have been located.



Repository structure

└── project
    ├── .gitignore
    ├── .env
    ├── requeriments.txt
    ├── README.md
    └── note
        └── note.txt


Improvements and expansion

Further research could be done on the reviews received in the apartments and in case a single owner has more than one apartment in which areas he has them.
