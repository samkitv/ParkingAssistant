# ParkingAssistant
This repository contains UI wireframes and designs for a college Parking Lot Android app.

Login Screen: The student/faculty logs into the app via a user ID and a password, provided by the college administration. Note that there's no provision for a sign-up feature as this is not an open application and is implemented only within the circle of college.

Dashboard: This screen shows the status of the parking lot, ie, number of open and reserved spots. There is also bottom nav bar with tabs for switching between 2-wheeler and 4-wheeler vehicles. This bar stays consistent throughout the app, to ensure fluid and fast experience. On clicking on the Available Spots, the user is redirected to the Map of the Parking lot. 

Parking Lot map: This screen allows the user to browse through the physical scene of the parking lot. In the top is a ribbon, showing all the available spots. The map image (which is scrollable) allows to go through the parking lot. On selecting an available spot, the user is asked to confirm their reservation and the spot is hence, reserved. An error toast message will be displayed if clicked on an invalid spot.

If there is any spot already reserved by the user, it will also be displayed on the Dashboard, from where they can either release the spot or open the map of the parking lot to find the spot, in case they could not locate the spot.

Account: This screen allows the user to manage other aspects of the app. Notices section displays any notifications & notices from the college. Support section gives the user ways to reach out to the administration with issues/suggestions for the app. This screen allows lets the user to check for updates or to logout from the app. 
