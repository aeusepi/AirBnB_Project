# AirBnB_Project

## Table of contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation<a name="installation"></a>
There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python.  The code should run with no issues using Python versions 3.*.
## Project Motivation<a name="motivation"></a>

For this project, to find what type of properties where listed on AirBnb for the city of Seattle, area of listing, most common features and pricing strategy. The goal of the analysis is understand for a new host the minumum requirments to compete with existing listings and what type of discunt to offer to beat well rated hosts. 


1. What are the location and the price per person per night of the Seattle Airbnb listings? 
2. What are the common perks offered and the average experience of the existing hosts?
3. What factors affect the pricing and does a new host require a discount to enter the market?

## File Description<a name="files"></a>
In the folder there are a Jupinter Notebook and a python file contianing useful functions deployed in the project. Finally, the folder also contains all the pictures used in the medium post.

## Results  <a name="results"></a>
1. On average the PPN hovers around 41$, with Lower Queen Ann (\~53$) the most expensive and Sewer Park the cheapest (\~ 30 $). The median weekly discount is around 10% whereas for monthly stays the median concession reaches 28%. Houses and Apartments are the most common property listed covering nearly 90% of the entire market.
2. The properties come with some common (internet, kitchen, dryer, heating, shampoo) and some extravagant (doorman, pool, gym, cats, iron) perks within the offered range. In Seattle, there are 2751 active hosts over the 3818 total listings. The majority are local (more than 80%). Only 20% are classified as SuperHost. The median host experience is around 2 yrs and, generally, every host is the owner of only one listing, with few outliers.
3. When setting up the price the key factors are (10 biggest coefficeints):
  - Positive:
    - The possibility to rent the full apartment or house
    - bedrooms and bathroom per guest
    - host response time
    - if the host is a superHost or not
    - the availability of an elevator in the building
    - the host response time
    - Neighbourood - Lower queen Ann
  - Negative: 
    - Property type (House or Apartment)
    - CX_Score (number and rating)

Ultimately, it is not clear if a brand new host should offer a discount. Indded, the qualification as SuperHost has a positive impact but the amount of reviews and    quality of rating has not. The neighbourood and specific perks provided can be helpful to boost the listing price. Overall, the new host needs to make a well   rounded listing considering the location, perks and crucial elements (bedroom and bathroom) withouth necessarly offer a discount to compete successfuly in the Seattle Airbnb market.

## Licensing, Authors, and Acknowledgements  <a name="licensing"></a>
* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Malven's Flexbox Cheatsheet](https://flexbox.malven.co/)
* [Malven's Grid Cheatsheet](https://grid.malven.co/)
* [Img Shields](https://shields.io)
* [GitHub Pages](https://pages.github.com)
* [Seattle Data 3](https://www.kaggle.com/code/ahmedhas93/seattle-data-3/data)

