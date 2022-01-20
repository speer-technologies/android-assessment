# Speer Technologies Android assessment


## Overview

The goal of this assessment is to build a basic Android application which demonstrates common tasks such as fetching data, parsing model entities from JSON, UI, and navigation. 

### Requirements

For this asessment you'll need to familiarize yourself with parts of the [GitHub REST API](https://docs.github.com/en/rest). The required features we'd like to see built are:

1. A search bar that enables us to fetch GitHub user profiles by username:
    - If no user exists with the username provided, present a "Not found" view
    - If the user exists, present a view with that user's:
        1. Avatar
        2. Username
        3. Name
        4. Description
        5. Follower count, i.e. *X followers*
        6. Following count, i.e. *X following*
2. A view which displays a list of the user's followers, as well as a view for who they're following 
    - We should be able to navigate to this view by tapping on the follower/following counts 
    - If a user in this list is tapped, it should navigate us to their profile view
3. The ability to navigate backwards through the navigation stack

Show us what you can do in no more than 24 hours. Keep a log of the time spent and include it with your submission. Note that there are no designs to follow for this assessment, so you have creative freedom when it comes to the layout and so on.

##### Bonus features

These features aren't mandatory, but if you have extra time and want to stand out feel free to add any of the following:

- Skeleton screens
- Pull to refresh
- Profile caching & cache invalidation


### Grading

This exercise will be graded on a number of criteria including, but not limited to: 
- Clean, readable, and well documented code
- Adherence to the SOLID principles
- Utilization of an architectural pattern


### Submission

Please commit all of your work to a *private* GitHub repository. When you are finished, invite the [rhys-at-speer](https://github.com/rhys-at-speer) account and email a link of the repository to [clement.shum@speer.io](mailto:clement.shum@speer.io) with the subject line:

**Android Developer Assessment - [Your Name]**.


#### Goodluck!