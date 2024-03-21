# Feature 1: Filter Events By City
"As a user,
I should be able to filter events by city
So that I can see a list of events taking place in that city."

### gherkin
Feature: Filter Events By City
Scenario: User filters events by city
    Given the user is on the events page
    When the user selects a city from the filter options
    Then the events displayed should be only those taking place in the selected city

# Feature 2: Show/Hide Event Details
"As a user,
I should be able to show/hide event details
So that I can control the level of information displayed about an event."

### gherkin
Feature: Show/Hide Event Details
Scenario: User shows/hides event details
    Given the user is viewing event details
    When the user toggles the show/hide details button
    Then the event details should be either shown or hidden based on the user's action


# Feature 3: Specify Number of Events
"As a user,
I should be able to specify the number of events I want to view
So that I can manage the volume of information displayed at once."

### gherkin
Feature: Specify Number of Events
Scenario: User specifies the number of events to view
    Given the user is on the events page
    When the user selects a number from the dropdown menu
    Then the specified number of events should be displayed on the page


# Feature 4: Use the App When Offline
"As a user,
I should be able to use the app when offline
So that I can access event information even without an internet connection."

### gherkin
Feature: Use the App When Offline
Scenario: User uses the app when offline
    Given the user has previously accessed event information
    When the user launches the app without an internet connection
    Then the app should display cached event data for offline use


# Feature 5: Add an App Shortcut to the Home Screen
"As a user,
I should be able to add an app shortcut to the home screen
So that I can quickly access the app without navigating through menus."

### gherkin
Feature: Add an App Shortcut to the Home Screen
Scenario: User adds an app shortcut to the home screen
    Given the user is on the app's homepage
    When the user selects the option to add a shortcut
    Then the app should prompt the user to add a shortcut to the home screen


# Feature 6: Display Charts Visualizing Event Details
"As a user,
I should be able to see charts visualizing event details
So that I can quickly understand trends or patterns related to events."

### gherkin
Feature: Display Charts Visualizing Event Details
Scenario: User views charts visualizing event details
    Given the user is viewing event details
    When the user navigates to the charts section
    Then the app should display charts illustrating relevant event data






