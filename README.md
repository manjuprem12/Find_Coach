# Find Your Coach
Find your coach
# Getting started with Find your coach

This project was created with Vue.js with Vuex and Vue Roters.

Frontend - Vue

Database - Fire Base

Git clone (https://github.com/manjuprem12/find-your-coach.git)
Path to the application (https://find-coach-vue.vercel.app/coaches)

## Table of Contents
- [Project Setup] (#project-setup)
- [Folder Structure](#folder-structure)
- [Available Scripts](#available-scripts)
  - [npm install](#npm-install)
  - [npm start](#npm-start)
- [Documentat Refered ].(#document-refered)

  ## Project Setup
1. Clone the repository
2. Navigate to the project directory
3. Install dependencies
4. Start the development server
## Folder Structure
After creation, project look like this:
```
my-app/
  README.md
  node_modules/
  package.json
  package-lock.json
  public/
    index.html
    favicon.ico
  src/
    components
        coaches
            CoachFilter.vue
            CoachForm.vue
            CoachItem.vue
        layout
            TheHeader.vue
        requests
            RequestItem.vue
        ui
            BaseBadge.vue
            BaseButton.vue
            BaseCard.vue
            BaseDialog.vue
            BaseSpinner.vue
    pages
        coaches
            CoachDetail.vue
            CoachRegistration.vue
            CoachList.vue
        requests
            ContactCoach.vue
            RequestsReceived.vue
        NotFound.vue
    store
        modules
            coaches
                actions.js
                getters.js
                index.js
                mutations.js
            requests
                actions.js
                getters.js
                index.js
                mutations.js
        index.js
    App.vue
    main.js
    router.js

```
## Available Scripts

In the project directory, you can run:

### `npm install`

Install all the packages used in the application it will create node modules.

### `npm run serve`

Runs the app in the development mode.\

## Documents Refered

You can learn more in the [Vue documentation] (https://vuejs.org/)

To learn Vuex, check out the .[vuex documentation ]. (https://vuex.vuejs.org/)

To learn Vue Router, checkout the .[Vue Router documentation ]. (https://router.vuejs.org/)

To learn vue styling, checkout the .[Vue style documentation ]. (https://vuejs.org/guide/essentials/class-and-style.html).

To learn Firebase, checkout the .[fire base documentation ]. (https://firebase.google.com/).
