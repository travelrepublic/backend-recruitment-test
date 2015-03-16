##Backend Recruitment Test

###What it is

At [Travel Republic](http://www.travelrepublic.co.uk) we know it's important to our customers that the price we show them is the one that they can book at.

We are constantly querying our partners for up to date pricing (it would be great if a few more of them pushed their prices to us!)

We'd like you to show us how you would go about building one small part of our system.

If you fancy having a go and are interested in our feedback send us details of how we can download your code to cstests@travelrepublic.co.uk

###What to do

Using the data in `flights.json` (each item in the array represents a flight).
Assuming it is midnight 1st January 2020 filter out flights that;

 - Depart before the current date/time.
 - Have a segment with an arrival date before the departure date.
 - Spend more than 2 hours on the ground. i.e those with a total gap of over two hours between the arrival date of one segment and the departure date of the next.

While solving the problem correctly is important this is an opportunity to show how you would go about structuring a solution to the problem.
Include as much or as little as you deem appropriate.
As a starting point it is highly likely we will want to adjust, add to or remove from these rules.

Have fun!
