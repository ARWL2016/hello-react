### Complete React Developer Course   

https://www.udemy.com/the-complete-react-web-app-developer-course/learn/v4/content 

- Udemy   
- Andrew Mead   
- Section 3  

####Contents
1. React Components (with nesting)  
2. JSX   
3. Props and State  
4. Webpack  

####General Notes
- This application retreives user input from a form field and renders it to the page, using React refs, props and state.  
- CommonJS Modules are used, but webpack config includes the babel-loader (is this needed for JSX?) 
- The server applies `app.use(express.static('public'));` but DOES NOT use sendFile(). So the browser grabs `index.html` by default.
- There are two display components, one container component and one root module - `app.jsx`. The root module simply renders the project to the page, but also serves as the entry point in webpack.  
- There is no divide between src and dist here, so the use of webpack is not that realistic.  