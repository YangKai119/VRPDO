The Vehicle Routing Problem with Delivery Options (VPRDO), and the related instances, are described in the following articles:
https://www.sciencedirect.com/science/article/pii/S0191261520304422
https://link.springer.com/article/10.1007/s00291-021-00633-0
https://www.sciencedirect.com/science/article/pii/S2192437621000121


The first line of each file is the name of the instance.
Then, each file is divided into four sections:
- First, the general description of the instance with: the maximum number of vehicles, their capacity, the number of locations, the number of customers to serve, the total number of options to serve all the customers, the number of priority levels for the options, and the number of types of locations.
- Second the description of the customer, with, for each of them: their id, and their demand.
- Third, the description of the locations, with: the id, the coordinate along the x-axis, the coordinate along the y-axis, the storage capacity (-1 if not applicable), the earliest possible service date at this location, the latest possible service date at this location, its type, and its service duration.
- Fourth, the description of the options, with: the id of the option, the id of the location where the option takes place, the id of the customer who can be served with the option, the priority level of the option, the service duration of the option, and its cost.

The travel cost and travel time between two locations is the euclidian distance between them.
The types of locations are: 0 - depot, 1 - shared delivery location, 2 - individual delivery location.
The capacity of shared delivery locations is expressed as a number of parcel, independantly of the demand of the associated customer.
