Project Proposal: Discover Jamestown

Tech Stack

- Frontend: 
    - React.js: (Web)
    - React Native: Maybe create this as a mobile app

- Backend:
    - Node.js with Express: To manage API requests, uer prefs, and integrations with APIs

- Database:
    - MongoDB: Store user data, save events, locations, things to do, etc., caching(?)

- Hosting:
    - Heroku or Railway: Host backend
    - Vercel or Netlify: Deploying frontend


Project Focus

Discover Jamestown is a web app that focus' on everything going on in Jamestown Rhode Island. The app will query multiple different
api's to gather data for events, places to stay, dining, things to do, visitor info, and more. It will be a great resource for 
tourists planning a visit or local residents to view events or other things to do around town.


Project Type

Web App: Users can login and create a favorites list or itinerary of things to do around town or they can just use the app without
logging in and view everything happening in Jamestown.


Project Goal

Create an elegant themed web app that allows users to search for all kinds of things they can do around Jamestown, RI.


User Demographic

- Local residents looking for events and things to do around town
- Tourists planning a trip to the island


Data and API

- OpenStreepMap or Mapbox: create an interactive map to show locations of things they are interested in
- Wikipedia: Historical data
- Eventbrite / AllEvents: Gather a list of all events happening in Jamestown
- Booking.com: Places to stay
- Tripadvisor / Yelp: Things to do (restaurants)
- May create my own API depending on what information I can't find


Project Approach

Database Schema:
    - User: username, email, locations, preferences
    - Location: name, coordinates, id
    - Lodging: name, location
    - Attractions: name, location
    - More to come...

Data Source:
    - Data will be coming from multiple different APIs
    - Show latency with loading screens and API errors

Sensitive Info:
    - User data will be limited to saving favorites and maybe creating an itinerary list of things to do
    - Authentication may or may not be necessary

Functionality / User Flow:
    - Users will enter the site at a homepage that shows the latest events, news, things happening etc in town
    - They will have the option to login to create their own profile to save/pin things to their account
    - There will be individual pages for each topic that will show data retrieved from a public api / my own api
    - Possible master search bar on website (haven't decided whether to build this)

Setup Backend and DB:
    - Setup Node/Express server
    - Setup MongoDB

Setup Frontend:
    - Use Vite to setup base React files

User Auth:
    - Probably have users login via Google account