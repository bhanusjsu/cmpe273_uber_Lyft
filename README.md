# cmpe273_uber_Lyft
Our project estimates the prices of uber and lyft for a User depending on his location inputs.

We use Google Autocomplete,Google Directions,Uber Developers API,Lyft Developers API.
We use Google waypoint API to solve the TSP problem.

To use the application,
First clone the Github cmpe273_uber_Lyft repository.
Requirements to Run the project:
Python 2.7
Flask
Flask-SQLAlchemy
Flask-migrate
MySQLdb
Geocoder
requests

After pip install the modules:
1)Run the requests1.py 
2)open localhost:9000
3)In the home page enter your location details  using google autocomplete and the places you want to go.
4)See the result page with shortest path mapped out on Google maps with a chart comparing the 
prices of Uber and Lyft depending on the type of the car you select.
5)The location details are stored automatically in the backend in MySQL.

We have deployed in AWS to loadbalance and autoscaling functionalities.
here is the link:
http://ec2-54-183-24-168.us-west-1.compute.amazonaws.com:9000/
