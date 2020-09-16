## Project Description:

### What is 311 Call?
311 is a non-emergency phone number that people can call in many cities to find information about services, make complaints, or report problems like graffiti or road damage.

The 311 San Francsico platform serves as a tool to accept, process, and address various requests/complains from the community, such as requests for city street cleaning, graffiti, etc.
In this project we use the 311-call data from the City of San Francisco to determine what are the major concerns of residents
of San Francsico, what zip codes have the most 311 requests, what source was used the most to submit request, 
if the month or day of the week affect the number of request.
and determine if there is any relation between the number of 311 calls per population, and income bracket.

## Hypothesis:
    
* Middle of the week would be more requests
* With higher income would be more requests 
* Number of service requests increase by population
* Number of service requests increase by shelter-in-place


## Data Sources Used:
* 311 call data from City of San Francisco
* Income and Population per zip code data form US Census of Bureau



## Data Cleaning:
* Pandas to remove unnecessary data from initial .csv file
* Slice Method to separate the date data and put it the different columns
* Use of US Census of Bureau anf google fu to retrieve zip code for each neighborhood, latitude and longitude and removing invalid zip codes.


## Challenges:
* Finding relevant data from US Census Bureau
* Retrieving zip codes with neighborhood for each service requests
* Finding the valid zip code reference for City of San Francisco
* Combining data from different sources in a correct way

## To do our analysis we used:
* Bar Chart
* Pie Chart
* Scatter Plot
* Heatmap
* Linear Regression


## notebook 311_Cases-A-Team.ipynb  requies the config.py file
<p>the content of config.py file should look like the following</p>
<pre><code>
census_key = "xxxxx"

g_key = "xxxxx"
</code></pre>
