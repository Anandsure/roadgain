# RoadGain

## RoadGain is a tool to identify and analyse real world roads and streets which can help control and improve the overall traffic conditions.

### Working principle
RoadGain follows the Braess's Paradox (Phenomenon that adding a road segment to a network can actually increase overall travel times, because of the tragedy of the commons. It follows that deleting certain road segments can decrease overall travel time). 
Braess's Paradox results in inefficiencies that can up to double overall travel time in a network, so isolating and removing roads that are contributing to congestion can help alleviate traffic congestion. These road segments can be converted to pedestrian-friendly streets and plazas, which can make neighborhoods less congested, more small-business friendly, and more human-centric!
This phenomenon has been repeatedly observed in the world, such as with the Cheonggyecheon Bridge in Seoul, South Korea, the road network in Stuttgart, Germany, or 42nd Street in New York City.

### Backend
We detect the roads that cause the congestion by using simple 10th grader triangle verification math. “If sum of any two sides is greater than the third , Verified” , its that simple. We also compute real world traffic data through all these sides from open street maps. If the time taken to traverse shortest side is greater than cumulative commute time of the other two sides, the shortest side can then be shut to increase traffic flow.

### Statistics
1. Indians spend more time in daily office commute than people in most countries in the world, with more than 2 hours on the road every day.
2. On an average Indians spend 7% of their day in commuting to office, averaging less than 3 minutes per kilometre. 
3. Traffic congestion during peak hours in just four major cities —Delhi, Mumbai, Bengaluru and Kolkata — costs the economy Rs 1.47 lakh crore annually.

(Statistics taken from TimesNow.com)

### Business Plan
We believe the truest & full use of RoadGain can only be made through collaborations with government authorities. To facilitate this, we intend for RoadGain to be free to use for the authorities which’ll ensure necessary  changes in the city’s planning are made.
RoadGain doesn’t need anything to help it sustain itself and there are almost no overhead costs since it uses Open Source tools. 
The only cost for us developers is to host it and to maintain it.
We also intend to deal the land saved by reducing a lane or street with the government and earn profits in return as a source of income and to facilitate maintenance of the software.

### Expenditure
The yearly price for hosting and maintaining a website (frontend + backend) is approximately Rs. 15,000. 

### Profit
Assuming we come up with a deal to receive Rs. 500 per sq. feet of redundant roads, we can find approximately thousands of sq. feet (let’s assume lowest case 1,000 sq. feet) in a metropolitan city. This way, we can earn about Rs. 5,00,000 per city. There are 4,000 cities in India according to nriol.com. Joining the dots, we now have a potential of ,
Rs. 4,000 x 5,00,000 sq. feet= A LOT OF MONEY
In just one country- India.
There are 195 countries in the world. Our profit margin can go really high!

### Competitors
We searched for competitors but no one provides a logical and self- sufficient solution like ours for the long run.
We also believe that if a competitor did exist, there would be next to no traffic jams in the world.

### What next
RoadGain relies on OSMNX to interact with Open Street Maps. We would hope to reduce wait time for generating dynamic maps by implementing our own graph library, likely in a lower level language.
