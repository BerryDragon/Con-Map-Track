# Con-Map-Track

The Convention Map Tracker is a web app that helps people find media or anime or furry conventions around the country and plan their trips easily. Instead of having to check multiple websites for details, prices, and directions, this app puts everything together in one place to make it easy for the user. Users can see how far a convention is from them, how many attendees were there last year (to get an idea of how many might go), and even get rough cost estimates for gas, plane tickets, and nearby hotels. The goal is to make it simple for anyone who likes going to conventions like anime, gaming, or comic cons to see what’s happening and decide if they can afford the trip.
The app’s main purpose is to take the stress out of travel planning, give an easier alternative to encourage you to go to the convention. Most con attendees have to check different sites for info on tickets, hotels, and transportation, and that can be time-consuming and discouraging. With this tracker, they’ll be able to type in their location and see all upcoming conventions, travel distances, and estimated costs that is around them. The data will pull from simple sources at first, probably stored in JSON or a basic database, or possibly install a web scraper to pull data from sites to constantly update. The project will also use location-based data to calculate travel distance and cost, a different version of Google Maps.
The key stakeholders for this project include convention attendees, event organizers to fund these. If the app were ever made public, travel agencies and advertisers could also become stakeholders since it would be an app for everyone. The main focus right now is to show I can design and build a working app using solid software planning and Agile methods. This means breaking the work into clear sprints, following a backlog, and keeping things organized in GitHub and on each desktop.
There are a few risks I already know about. The first is the limited time for development, since this project only spans eight weeks. Gathering real data could also take longer than expected, especially for accurate pricing and such (Thus my web scraper idea could be implemented). Another challenge will be making sure the app looks good and runs well on both desktop and mobile. I plan to manage these risks by keeping the features realistic focusing first on convention lookup, map display, and simple cost estimation before adding anything fancy. I’ll also make sure to test often, and update based on what works best.
For the success criteria, I’ll know I’ve met my goals when the app can show conventions with distance, cost, and attendance info (Probably when you hover your mouse over the location or distance line). The travel estimate feature should give users a general idea of what it would cost to drive or fly to that event. The interface should load fast and show accurate data. Each feature will match a user story from the backlog, and the whole app will be managed through version control on GitHub with proper commits, branches, and documentation. If all those parts work together smoothly by the end, I’ll consider it a success.
I’m keeping this project ambitious enough to show real-world application. By the end, I’ll have something useful that ties together data, mapping, and cost estimation all while following the Agile process. I honestly think this could be very doable and it could serve a lot of purpose for today’s societal needs.


Two-Sprint Plan
Sprint 1 (Weeks 2-4): Setup and Core Features
•	Create Github repo and file structure
•	Build homepage and map interface (Google Maps or Mapbox API sounds good)
•	Add search function for conventions
•	Display convention markers on the map
•	Store basic data in JSON or database
Goal: Have a working prototype that shows conventions and distance from the user.
Sprint 2 (Weeks 5-7): Enhancements and Integration
•	Add travel cost estimation (car and flight)
•	Include nearby hotel listings
•	Show attendance from previous year
•	Improve mobile design
•	Conduct testing and fix bugs
Goal: A Working version ready for demo with realistic data and smooth performance.

Week 1: Planning, research, and writing the project charter. 

Week 8: Final testing, bug fixes, and submission.

Personal Backlog - User Stories

ID: CMT-1
As a user, I want to search for conventions by name so I can find events easily.
Acceptance Criteria: Search returns results within 1 second, partial matches work (like typing "Comic" shows "Comic Con"), and it shows "No results" if nothing matches.

ID: CMT-2
As a user, I want to see convention locations on a map so I know where they're held.
Acceptance Criteria: Map marker appears at the right spot, map centers on the convention when selected, and hovering over the marker shows the convention name.

ID: CMT-3
As a user, I want to know how far conventions are from my location.
Acceptance Criteria: Distance is shown in miles, calculation is accurate within about 5 miles, and it updates if I change my location.

ID: CMT-4
As a user, I want to see gas cost estimates for driving to conventions.
Acceptance Criteria: Cost is calculated using distance and average fuel prices, assumes a typical car gets 25-30 MPG, and shows the total in dollars. (Possibly have to put in some type of calculation to ask the user how many MPG their car gets in the city and on the highway)

ID: CMT-5
As a user, I want to compare flight and driving costs.
Acceptance Criteria: Shows estimated roundtrip flight price, compares it to driving cost, and labels which option is cheaper.

ID: CMT-6
As a user, I want to see nearby hotels so I can plan where to stay.
Acceptance Criteria: Displays 3-5 hotels near the convention, shows hotel names and nightly rates, and lists how far each one is from the venue.

ID: CMT-7
As a user, I want to see how many people attended last year.
Acceptance Criteria: Previous year's attendance number is visible for each convention, shows "N/A" if the data isn't available, and the number is clearly labeled.

ID: CMT-8
As a user, I want to filter conventions by state or distance.
Acceptance Criteria: Can filter by radius like 100, 250, or 500 miles, can filter by state using a dropdown, and results update right away.

ID: CMT-9
As a user, I want to click on conventions to see more details.
Acceptance Criteria: A detail panel opens with full information including costs, hotels, and attendance, and there's an X button to close it. Cannot forget links to the website either.

ID: CMT-10
As a user, I want the app to load quickly so I'm not waiting around.
Acceptance Criteria: Main page loads in under 3 seconds, search results show up within 1 second, and there's no lag when switching between views.

ID: CMT-11
As a user, I want the app to work well on my phone.
Acceptance Criteria: Layout adjusts properly for phone screens (320px and up), all buttons are easy to tap, and the map and search work on mobile browsers.

ID: CMT-12
As a user, I want to see updated convention info each year.
Acceptance Criteria: Convention data can be updated through the JSON file, new conventions show up after the data refreshes, and past events get archived or marked as inactive.


