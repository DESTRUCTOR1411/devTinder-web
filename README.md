# DevTinder

- create vite app
- remove unecessary code and create a hello World app
- Install tailwind css
- Install Daisyui
- Add Navbar component to App.jsx
- create a navbar saperate navbar file
- install react router dom 

- Create BrowserROuter > Routes > ROute= /Body > RouteChildren
- Create an Outlet in your Body Component
- Create a footer

- Create a login page 
- Install Axios

- CORS install cors in backend => add middleware to with configurations :    origin: URL of frontend ,   credentials=true {

    withCredentials: true ensures that cookies and HTTP authentication data (like sessions or tokens) are sent and received correctly between the client and the server.
    It's mainly required when you're working with:
        1.Cookies for authentication (e.g., JWT stored in cookies).
        2.Sessions managed on the server using cookies (e.g., express-session).
        3.CORS (Cross-Origin Resource Sharing) requests when the frontend (e.g.,      localhost:3000) is different from the backend (e.g., localhost:8000).

}

- whever you are making api call so pass axios => { withCredentials: true}
- 


BODY
    NavBar
    Outlet-{Route=/ => Feed
            Route=/login => Login
            Route=/profile => Profile
            Route=/connections => Connections
        }
    Footer

