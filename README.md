## Feature 1: Filter Events By City
"As a user,<br>
I should be able to filter events by city<br>
So that I can see a list of events taking place in that city."<br>

### gherkin
Feature: Filter Events By City <br>
Scenario: User filters events by city<br>
    Given the user is on the events page<br>
    When the user selects a city from the filter options<br>
    Then the events displayed should be only those taking place in the selected city<br>

## Feature 2: Show/Hide Event Details
"As a user,<br>
I should be able to show/hide event details<br>
So that I can control the level of information displayed about an event."<br>

### gherkin
Feature: Show/Hide Event Details<br>
Scenario: User shows/hides event details<br>
    Given the user is viewing event details<br>
    When the user toggles the show/hide details button<br>
    Then the event details should be either shown or hidden based on the user's action<br>


## Feature 3: Specify Number of Events
"As a user,<br>
I should be able to specify the number of events I want to view<br>
So that I can manage the volume of information displayed at once."<br>

### gherkin
Feature: Specify Number of Events<br>
Scenario: User specifies the number of events to view<br>
    Given the user is on the events page<br>
    When the user selects a number from the dropdown menu<br>
    Then the specified number of events should be displayed on the page<br>


## Feature 4: Use the App When Offline
"As a user,<br>
I should be able to use the app when offline<br>
So that I can access event information even without an internet connection."<br>

### gherkin
Feature: Use the App When Offline<br>
Scenario: User uses the app when offline<br>
    Given the user has previously accessed event information<br>
    When the user launches the app without an internet connection<br>
    Then the app should display cached event data for offline use<br>


## Feature 5: Add an App Shortcut to the Home Screen
"As a user,<br>
I should be able to add an app shortcut to the home screen<br>
So that I can quickly access the app without navigating through menus."<br>

### gherkin
Feature: Add an App Shortcut to the Home Screen<br>
Scenario: User adds an app shortcut to the home screen<br>
    Given the user is on the app's homepage<br>
    When the user selects the option to add a shortcut<br>
    Then the app should prompt the user to add a shortcut to the home screen<br>


## Feature 6: Display Charts Visualizing Event Details
"As a user,<br>
I should be able to see charts visualizing event details<br>
So that I can quickly understand trends or patterns related to events."<br>

### gherkin
Feature: Display Charts Visualizing Event Details<br>
Scenario: User views charts visualizing event details<br>
    Given the user is viewing event details<br>
    When the user navigates to the charts section<br>
    Then the app should display charts illustrating relevant event data<br>


### Serverless Functions
In this project, I'll use serverless functions to do the heavy lifting of fetching upcoming events from the Google Calendar API. <br> 
These functions will be like little helpers that work on-demand, scaling up or down as needed, so I don't have to worry about managing servers or infrastructure. <br> 
This not only makes things easier for me but also ensures the app runs smoothly, saves on costs, and stays available for users whenever they need it.




