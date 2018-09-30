“SnakeEye”  is an AI-based system integration platform that uses Object detection & Deep learning techniques to detect & classify F&B into three types
Untouched
Leftovers
Consumed

Our algorithm will then count the number of times each category has appeared and correspondingly update it in the database.

Sources - 
Video demo - https://youtu.be/R-N4GLBP7N8 <br>
Presentation - https://bit.ly/2zGEklL <br>
Dashboard - https://bit.ly/2P11CI2 <br>

------------------------------------------------------------------------------------------------------------------------------


Current Scenario:

Presently, there is lot of manual intervention involved in terms of counting the wasted meals. 
Then the numbers are entered manually in a spreadsheet.
Wastage(%) is then computed based on the capacity of the flight.

Proposed solution:

Having a system in place that automatically counts & classifies meals 
Store the count in the database along with other details of the flight from the API ( Capacity, Number of people, Gender, Age, Diet & so on )
Dashboarding everything in a single place for management to track.

------------------------------------------------------------------------------------------------------------------------------


Core Technology:

1. Deep learning:
R-CNN implemented using Python & Tensorflow

2. API’s Provided by SIA:
    /flightschedule, /flight/passenger, /equipment/loadplan - Using Postman collection to fetch data into the database.

3. Dashboarding:
    Node.js, D3.js and MongoDB

4. Predictive Modeling:
    Python, Scikit-Learn, Numpy & Pandas






