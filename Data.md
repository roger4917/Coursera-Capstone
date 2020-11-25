# Data
Based on definition of our problem, factors that will influence our decision are:
- number of existing restaurants in the neighborhood (any type of restaurant)
- distance of neighborhood from city center

We decided to use regularly spaced grid of locations, centered around city center, to define our neighborhoods.
Following data sources will be needed to extract/generate the required information:
* centers of candidate areas will be generated algorithmically and approximate addresses of centers of those areas will be obtained using Google Maps API reverse geocoding
* number of restaurants and their type and location in every neighborhood will be obtained using Foursquare API
* coordinate of Bari center will be obtained using Google Maps API geocoding of historical site/museum Castello Svevo in Bari
