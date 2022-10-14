# Coding Challenge - Bored API

Create simple React app using https://www.boredapi.com/api/activity API.

## Basic task description :memo:

Create a simple react application using redux for state management. When the user clicks the button, data should be fetched from API and displayed on the screen in the simple card. Display all fetched data in a scrollable list (from newer to older). When the user clicks the save button, save data in the app state (use redux). On the activities page, the user should see all saved activities and also can search them by activity name. When the user clicks on a single activity card, the user should be redirected to the new page, the single activity page. User can also delete saved activity.

## Acceptance Criteria :white_check_mark:

- Create new react app ([see this link](https://reactjs.org/docs/create-a-new-react-app.html)).
- Create reusable components (button, card, list, etc.)
- For state management use redux ([see this link](https://redux.js.org/introduction/getting-started))
- fetch new data with simple GET request
  - API - https://www.boredapi.com/api/
- on get action - fetch ne activity from API
- on save action - save fetched data into the app state
- on delete action - delete saved activity
- on search action - show activities based on searched activity name
- app needs to have four pages
  - use react router for routing ([see this link](https://v5.reactrouter.com/web/guides/quick-start))
  - pages:
    - home page with "/" route
    - saved actions page with "/actions" route
    - single saved action page with "/actions/:id"
    - not found page - every other not defined route "\*"
- follow figma design ([link to design](https://www.figma.com/file/jx1AadZg8Rf0k5ZL9GBwue/bored))
- responsive stlye

## When finished :checkered_flag:

When finished, save your project on github and add me as contributor.
