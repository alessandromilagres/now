## SCENARIO DESCRIPTION ##
A single person lands in paris, no hotel, no plans.  First time there, wants to spend an afternoon and evening on the town.

## INTENTS ##
* Book a hotel in Paris
* Obtain Transportation from Airport
* Find an interesting activity for the afternoon
* Find lunch near museum
* Find a local jazz group playing in a fun part of town
* Find dinner near music venue
* Voice to Voice Translation

## REQUIREMENTS ##
* Each "place" should include a list of options for transportation from expected location.  When "place" is next "place" then from current location.

## FEATURES ##
The following core features are to be included for showing off in the app
* Transportation Options and Ride Booking
* Activities and Events listing and Booking
* Restaurants listing and Booking
* Hotel Listing and booking


## HIGH LEVEL WORKFLOW ##
1. HOME 

2. Discover and Pick Hotel
- Inner Dialog : "Just arrived at airport, while standing in line at customs it's a good time to pick a suitable hotel."
- Actions: Show some hotel details, Pick Hotel

3. Discover and Pick Transportation options from Airport
- Inner Dialog: "Got a hotel, what's are my options to get there."
- Actions: Show transportation options, Drill down into some options, pick UBER

4. Find an interesting activity for the afternoon
- Inner Dialog: "Now that i have a 40 minute cab ride, i may as well look around for some things to do"
- Actions: Browse suggested activities near my hotel, filter to museums, look at 2 museum details, pick a museum

5. Find lunch near museum
- Inner Dialog: "I just got to my hotel and ready to go to the museum, but now i'm hungry.  It's the middle of the afternoon and a lot of places seem closed (french!), where can i find a decent meal?"
- Actions: Browse restaruants with filters (walking distance from museum, open, price range, french), Pick a restaraunt.

6. Find a local jazz group playing in a fun part of town
- Inner Dialog: "This excellent french food is reminding me of my dormant love for traditional Jazz.  Where can i find a decent jazz band playing tonight in a bohemian atmosphere?"
- Actions: Find live music within 1 mile radius of my hotel, filter by type and atmosphere. Pick a place.

7. Find dinner near music venue
- Inner Dialog: "Now that i'm leaving to check out a jazz trio, let's find a suitable restaurant near the venue"
- Actions: Browse restaurants near the venue, drill down to some options, pick one.

