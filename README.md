# Schedule-a-Ride

Analyzing the Uber “Schedule a Ride” option from a graph algorithms and optimization perspective. This code accompanies the post in my blog http://withoutlossofgenerality.com/schedule-a-ride-uber-algorithms/.

We know that Uber has a “schedule a ride” option where you can schedule a ride days-in-advance by giving a start time, pick-up location and destination. Given a set of “schedule a ride” requests for a given day, engineers at Uber have to figure out

1. Whether or not all those requests can be satisfied
2. How many drivers will be needed if all requests are to be satisfied?
3. Given that only K drivers are available, how many requests can be satisfied at maximum?

In this project, we try to figure out how such a task may be accomplished given the Los Angeles Uber Movement dataset and a set of “schedule a ride” requests generated using a
multi-modal Gaussian distribution. 
