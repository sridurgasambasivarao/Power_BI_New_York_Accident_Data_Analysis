This analysis is based on motor vehicle collisions reported by the New York City Police Department from January-August 2020. Each record represents an individual collision, including the date, time and location of the accident (borough, zip code, street name, latitude/longitude), vehicles and victims involved, and contributing factors.

More than 25,000 records borough information was missing. So implemented reverse geocoding using geopy with Nominatim, including a 1 second delay between each request to comply with OpenStreetMap’s usage policy. This is implemented in python. We are iterating and saving the results progressively, so we don’t lose progress. Resulting file is named as cleaned_borough_na.

**Questions trying to answer:**

* Which borrow had the highest number of accidents?
* What were the peak times for accidents?
* Which intersections or street segemnts are the most accident-prone?
* How many accidents resulted in fatalities vs injuries?
* What proportion of accidents involved, pedestrians, motorists or cyclists?







