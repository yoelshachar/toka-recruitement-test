# Toka FSD Recruitment Test
**Create a full stack app using Node.js, express, Vue and vuex.**

If you're not familiar with `Vue`, `Vue CLI` and `Vuex`, please read their documentation first. 
Our apps was written in `Vue 2` and are tightly coupled with Vuex. 
Make sure you understand Vue component's lifecycle before start - it will help you write your components logic better.

> Plase avoid using `typescript` for this project

## Backend
- Create express web server on port 3000
- Create web socket server on the same port
- Listen to web socket messages sent from frontend
- Response to messages with a data model containing fields required by UI design

## Frontend
 Create Vue app in project root named 'app' using Vue CLI's `vue create` command
- Use Vuex for state management
- Use Less as a css preprocessor
- Use Vue Router
- Include attached `style.less` as a base style
- Include and use `bootstrap.grid.min.less`

### Implementation
- Implement attached `wireframe.pdf`
- Use Vuex `mapGetters/ mapActions` from within Vue components/ views when suitable
- Connect to backend server using `WebSocket`
- Show Splash screen until web socket is connected
- Send API request over web socket connection
- Show loading screen while waiting to API response
- Bind data once received from backend
- Implement dynamic filters & client side search

## Build and Serve
- Configure Vue app to put its dist files inside `./server/public`
- Serve Vue app dist files from `./server/public` over http

### Bonus
- Use subtle css animations to enhance user experience as you wish
- Write at least 4 unit tests for backend and frontend 
- Deploy all with `Dockerfile` & `docker-compose.yaml`
