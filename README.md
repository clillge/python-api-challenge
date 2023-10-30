# python-api-challenge

Did not run into too many issues on this assignment.

The only primary issue was that only around 30% of the cities found through citipy contained a country id. Since they were rejected without it I had to increase the size of the random latitude and longitude function to compensate and still allow myself to find 500 valid cities to work with.

The run time did increase as a result, with it taking roughly 5min on average to find nearly 2000 cities, which gave just over the amount of cities necessary for the assignment after removing the ones without a country id.

Overall an interesting and fun challenge which makes me want to study and work with even more api's in future assignments.