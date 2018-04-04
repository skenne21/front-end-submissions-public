## Project Name:skywatch

#### Check In :1

#### Project Pitch:
Build an app for people who want to find out about current space and other related events in the area and what the weather conditions and time for observing them watching them.  

### Deliverables
#### Stack:

React
Redux
Router
middleWare
scss

#### APIs:
Predict the Sky: http://predictthesky.org/developers.html
NASA open source: https://api.nasa.gov/api.html#apod

#### Wireframes
[!wireframe-homepage](https://www.facebook.com/photo.php?fbid=902481468988&set=a.902481463998.1073741835.124702253&type=3&theater)


#### Waffle & Github
[waffle](https://waffle.io/skenne21/sky-watch)
[Github](https://github.com/skenne21/sky-watch)


#### Order Of Attack
Fetching data from API and setting up user information
set up logic for passing the information in-store/actions/reducers
move fetch call into middleware/sagas
fetch on search
setup routes and paths on button clicks
displaying information
saving user information in a login
loading giff when fetching


#### MVP
keep track of the user when login in
-name, saved events

the Homepage displays a picture of the day from NASA

able to search the city for current location

have the user be able to search for events in the area from different types of events: 
be able to search for 
meteor_showers     
lunar_eclipses          
planets     
moon_phase     
comets     


#### Nice To Haves:
allow the user to be able to see past events / upcoming events they are interested in.
send alerts for events coming up to the user
allow users to meet up with each other for an event


#### Biggest Challenges
getting the location of a user
working with saga or middleware
getting the location of the user


#### Instructor Notes

#### Deliverables for next checkin:
