# Lab: Where's The Train?


###Correctly Implemented:
I believe I have implemented everything correctly - the one thing I am uncomfortable with is the scope of the "map" variable within my function (and perhaps overusing the init function). Also, I wasn't sure how much information we need to show in the markers, but they just are labeled with the TripID of the trip they represent.

###Collaborations/Discussions:
I haven't collaborated/discussed with anyone, really

###Time Commitment:
Like 5-6ish hours?

###Possible to request real-time data?
Using XMLHttpRequest, the data we get back represents a snapshot of the moment in time that the MBTA server responds to the request and sends back the data. Thus, the data, as indicated by the timestamp we recieve back, is not in real-time. We'd have to either use another protocol or be continually executing  XMLHttpRequests (which isn't even quite real-time) to be updating data as it updates at MBTA. 