# reactjs-interview-questions
reactjs-interview-questions


    5: React is an open source, JavaScript library for developing user interface (UI) in web application. React is developed and released by Facebook. Facebook is continuously working on the React library and enhancing it by fixing bugs and introducing new features.  
    
	  132: ReactJS is a simple, feature rich, component based JavaScript UI library. It can be used to develop small applications as well as big, complex applications. ReactJS provides minimal and solid feature set to kick-start a web application. React community compliments React library by providing large set of ready-made components to develop web application in a record time. React community also provides advanced concept like state management, routing, etc., on top of the React library. 
   
	  169: To develop lightweight features such as form validation, model dialog, etc., React library can be directly included into the web application through content delivery network (CDN). It is similar to using jQuery library in a web application. For moderate to big application, it is advised to write the application as multiple files and then use bundler such as webpack, parcel, rollup, etc., to compile and bundle the application before deploying the code. 
   
	  182: The serve is a lightweight web server. It serves static site and single page application. It loads fast and consume minimum memory. It can be used to serve a React application. Let us install the tool using npm package manager in our system. 
   
	  217: $Babel is a JavaScript compiler which compiles many variant (es2015, es6, etc.,) of JavaScript into standard JavaScript code supported by all browsers. React uses JSX, an extension of JavaScript to design the user interface code. Babel is used to compile the JSX code into JavaScript code.$ 
   
	  228: Create React App is a modern CLI tool to create single page React application. It is the standard tool supported by React community. It handles babel compiler as well. Let us install Create React App in our local system. 
   
	  243: React library is built on a solid foundation. It is simple, flexible and extensible. As we learned earlier, React is a library to create user interface in a web application. React’s primary purpose is to enable the developer to create user interface using pure JavaScript. Normally, every user interface library introduces a new template language (which we need to learn) to design the user interface and provides an option to write logic, either inside the template or separately.  
   
	  248: A JavaScript extension to design user interface. JSX is an XML based, extensible language supporting HTML syntax with little modification. JSX can be compiled to React Elements and used to create user interface. 
   
	  325: Next, run the application and open the browser. The output of the application is as follows: 
   
	  388: •We are using unpkg CDN. unpkg is an open source, global content delivery network supporting npm packages. 
   
	  408: The react-app is a placeholder container and React will work inside the container. We can use any name for the placeholder container relevant to our application. 
   
	  458: The content of the React application is as follows: 
   
	  529: •The index.js - Entry point of our application. It uses ReactDOM.render method to kickstart and start the application. The code is as follows: 
   
	  542: React.StrictMode is a build-in component used to prevent unexpected bugs by analysing the component for unsafe lifecycle, unsafe API usage, depreciated API usage, etc., and throwing the relevant warning. 
   
	  618: Open your favorite browser and go to http://localhost:3000. The result of the application is as shown below: 
   
	  854: As we learned earlier, React JSX is an extension to JavaScript. It enables developer to create virtual DOM using XML syntax. It compiles down to pure JavaScript 
   
	  878: Here, cTime used in the JSX using expression. The output of the above code is as follows, ReactJS      
   
	  908: The output is as follows: 
   
	 1239: The complete code to do it using CDN in a webpage is as follows: 
  
	 1299: The complete code of index.js is as follows: 
  
	 1315: The complete code to do it using CDN in a webpage is as follows: 
  
	 1421: Now, we have successfully created our FormattedDate React component. The complete code is as follows: 
  
	 1564: Now, we have successfully created the component to render the expense items into HTML table. The complete code is as follows: 
  
	 1626: The complete code of index.js is as follows: 
	 1700: The alternative lambda syntax is as follows: 
	 1712: The alternate lambda syntax is as follows: 
	 1799: The complete and updated code is as follows: 
	 1835:     console.log("The mouse is at (" + e.clientX + ", " + e.clientY + ")"); } 
	 1862: The final and complete code of the ExpenseEntryItemList is as follows: 
	 1873:     handleMouseOver(e) {         console.log("The mouse is at (" + e.clientX + ", " + e.clientY + ")");     }  
	 1944: The simple representation of the state is as follows: 
	 1952: The signature of the setState API is as follows: 
	 1954: A simple example to set / update name is as follows: 
	 1956: The signature of the setState with function is as follows: 
	 1965: A simple example to update the amount using function is as follows: 
	 1978: React component with internal state is called Stateful component and React component without any internal state management is called Stateless component. React recommends to create and use as many stateless component as possible and create stateful component only when it is absolutely necessary. Also, React does not share the state with child component. The data needs to be passed to the child component through child’s properties. 
	 1979: An example to pass date to the FormattedDate component is as follows: 
	 2023: The complete source code of the Clock component is as follows: 
	 2128: The complete code of the render() method is as follows: 
	 2163: Finally, the updated code of the ExpenseEntryItemList is as follows: 
	 2180:         console.log("The mouse is at (" + e.clientX + ", " + e.clientY + ")");     } 
	 2263: React introduces an entirely new concepts called React Hooks from React 16.8. Even though, it is a relatively new concept, it enables React functional component to have its own state and life-cycle. Also, React Hooks enables functional component to use many of the feature not available earlier. Let us see how to do state management in a functional component using React Hooks in this chapter. 
	 2266: The general signature of useState() Hook is as follows: 
	 2297: The complete source code of the Clock component is as follows: 
	 2357:     console.log("The mouse is at (" + e.clientX + ", " + e.clientY + ")"); } 
	 2408: The complete code of the ExpenseEntryItemListFn is as follows: 
	 2418:         console.log("The mouse is at (" + e.clientX + ", " + e.clientY + ")");     }  
	 2514: The signature of the API is as follows: 
	 2523: The signature is as follows: 
	 2529: The signature of the API is as follows: 
	 2533: This is a static method and does not have access to this object. 
	 2535: The signature of the API is as follows: 
	 2643: The signature of the useEffect() api is as follows: 
	 2674: Now, we have updated the Clock component and the complete source code of the component is as follows: 
	 2805: In short, containment is an excellent feature to pass arbitrary user interface content to the component. 
	 2812: And the layout render logic is as follows: 
	 2852: Render props is an advanced concept used to share logic between React components. As we learned earlier, a component can receive arbitrary UI content or React elements (objects) through properties. Usually, the component render the React elements it receives as is along with its own user interface as we have seen in children and layout concept. They do not share any logic between them.  
	 2969: The complete code of the Pager component is as follows: 
	 3082:         console.log("The mouse is at (" + e.clientX + ", " + e.clientY + ")");     }  
	 3267: The complete source code of the component is as given below: 
	 3349: The complete code of index.js is as follows: 
	 3437: •nedb is a datastore used to store the expense data. 
	 3438: •cors is a middleware for express framework to configure the client access details 
	 3602: •setItems is again used to format and store the items in the state. 
	 3821: The complete code of the ExpenseForm component is as follows: 
	 4261: The interactive version of the form is as follows: 
	 4264: In web application, Routing is a process of binding a web URL to a specific resource in the web application. In React, it is binding an URL to a component. React does not support routing natively as it is basically an user interface library. React community provides many third party component to handle routing in the React application. Let us learn React Router, a top choice routing library for React application. 
	 4317: Here, useParams is a custom React Hooks provided by React Router component. 
	 4526: React redux is an advanced state management library for React. As we learned earlier, React only supports component level state management. In a big and complex application, large number of components are used. React recommends to move the state to the top level component and pass the state to the nested component using properties. It helps to some extent but it becomes complex when the components increases.  
	 4533: Actions: Action is an plain object with the type of the action to be done and the input (called payload) necessary to do the action. For example, action for adding an item in the store contains ADD_ITEM as type and an object with item’s details as payload. The action can be represented as: 
	 4559: All parameters are optional and it returns a HOC (higher order component). A higher order component is a function which wraps a component and returns a new component. 
	 4901: Animation is an exciting feature of modern web application. It gives a refreshing feel to the application. React community provides many excellent react based animation library like React Motion, React Reveal, react-animations, etc., React itself provides an animation library, React Transition Group as an add-on option earlier. It is an independent library enhancing the earlier version of the library. Let us learn React Transition Group animation library in this chapter. 
	 4904: React Transition Group library is a simple implementation of animation. It does not do any animation out of the box. Instead, it exposes the core animation related information. Every animation is basically transition of an element from one state to another. The library exposes minimum possible state of every element and they are given below: 
	 4974: The complete source code of the component is as follows: 
	 5150: TransitionGroup is a container component, which manages multiple transition component in a list. For example, while each item in a list use CSSTransition, TransitionGroup can be used to group all the item for proper animation. 
	 5296: Once the application is build, the application is available under build/static folder. 
	 5955: The complete source code of the component is as follows: 
	 6029: React is one of the most popular and highly recommended UI frameworks. True to its popularity, it is being developed for a very long time and actively maintained. Learning react framework is a good starting point for the front end developers and will surely help them to improve their professional career. 






  Line  132: ReactJS is a simple, feature rich, component based JavaScript UI library. It can be used to develop small applications as well as big, complex applications. ReactJS provides minimal and solid feature set to kick-start a web application. React community compliments React library by providing large set of ready-made components to develop web application in a record time. React community also provides advanced concept like state management, routing, etc., on top of the React library. 
	Line  182: The serve is a lightweight web server. It serves static site and single page application. It loads fast and consume minimum memory. It can be used to serve a React application. Let us install the tool using npm package manager in our system. 
	Line  217: $Babel is a JavaScript compiler which compiles many variant (es2015, es6, etc.,) of JavaScript into standard JavaScript code supported by all browsers. React uses JSX, an extension of JavaScript to design the user interface code. Babel is used to compile the JSX code into JavaScript code.$ 
	Line  248: A JavaScript extension to design user interface. JSX is an XML based, extensible language supporting HTML syntax with little modification. JSX can be compiled to React Elements and used to create user interface. 
	Line  283: Used to create React elements. It expects three parameters: 
	Line  288: Used to render the element into the container. It expects two parameters: 
	Line  430: We can use the same steps to use React in the existing website as well. This method is very easy to use and consume React library. It can be used to do simple to moderate feature in a website. It can be used in new as well as existing application along with other libraries. This method is suitable for static website with few dynamic section like contact form, simple payment option, etc., To create advanced single page application (SPA), we need to use React tools. Let us learn how to create a SPA using React tools in upcoming chapter. 
	Line  520: •react and react-dom are core react libraries used to develop web application. 
	Line  522: •react-scripts are core react scripts used to build and run application. 
	Line  523: •@testing-library/jest-dom, @testing-library/react and @testing-library/userevent are testing libary used to test the application after development. 
	Line  542: React.StrictMode is a build-in component used to prevent unexpected bugs by analysing the component for unsafe lifecycle, unsafe API usage, depreciated API usage, etc., and throwing the relevant warning. 
	Line  544: The index.css - Used to styles of the entire application. Let us remove all styles and start with fresh code. 
	Line  553: •App.css - Used to style the App component. Let us remove all styles and start with fresh code. 
	Line  554: •App.test.js - Used to write unit test function for our component. 
	Line  555: •setupTests.js - Used to setup the testing framework for our application. 
	Line 1044: React component can also be created using plain JavaScript function but with limited features. Function based React component does not support state management and other advanced features. It can be used to quickly create a simple component.  
	Line 1510: The map function accepts a collection and a mapping function. The map function will be applied to each and every item in the collection and the results are used to generate a new list. 
	Line 1828: •Once the parent node is found, event handler access the list of the css class attached to the parent node and adds ‘highlight’ class using add method. classList is the standard DOM property to get list of class attached to the node and it can be used to add / remove class from a DOM node. 
	Line 2272: •currentDateTime - Variable used to hold current date and time (returned by setState() 
	Line 2273: •setCurrentDate() - Function used to set current date and time (returned by setState()) 
	Line 2509: constructor() - Invoked during the initial construction phase of the React component. Used to set initial state and properties of the component. 
	Line 2522: shouldComponentUpdate() - Invoked during the update phase. Used to specify whether the component should update or not. If it returns false, then the update will not happen. 
	Line 2534: getSnapshotBeforeUpdate - Invoked just before the rendered content is commited to DOM tree. It is mainly used to get some information about the new content. The data returned by this method will be passed to ComponentDidUpdate() method. For example, it is used to maintain the user’s scroll position in the newly generated content. It returns user’s scroll position. This scroll position is used by componentDidUpdate() to set the scroll position of the output in the actual DOM. 
	Line 2852: Render props is an advanced concept used to share logic between React components. As we learned earlier, a component can receive arbitrary UI content or React elements (objects) through properties. Usually, the component render the React elements it receives as is along with its own user interface as we have seen in children and layout concept. They do not share any logic between them.  
	Line 3436: •express is used to create server side application. 
	Line 3437: •nedb is a datastore used to store the expense data. 
	Line 3590: •fetch api is used to fetch the item from the remote server. 
	Line 3591: •setItems is used to format and store the items in the state. 
	Line 3601: •fetch api is used to delete and fetch the item from the remote server. 
	Line 3602: •setItems is again used to format and store the items in the state. 
	Line 3674: •Controlled component: In controlled component, React provides a special attribute, value for all input elements and controls the input elements. The value attribute can be used to get and set the value of the input element. It has to be in sync with state of the component. 
	Line 4277: Here, to attribute is used to set the target url. 
	Line 4278: Switch & Route - Both are used together. Maps the target url to the component. Switch is the parent component and Route is the child component. Switch component can have multiple Route component and each Route component mapping a particular url to a component. 
	Line 4290: Here, path attribute is used to match the url. Basically, Switch works similr to traditional switch statement in a programming language. It matches the target url with each child route (path attribute) one by one in sequence and invoke the first matched route. 
	Line 4291: Along with router component, React router provides option to get set and get dynamic information from the url. For example, in an article website, the url may have article type attached to it and the article type needs to be dynamically extracted and has to be used to fetch the specific type of articles. 
	Line 4354: Here, useRouteMatch returns the matched path and the target url. url can be used to create next level of links and path can be used to map next level of components / screens. Creating navigation 
	Line 4538: Reducers: Reducers are pure functions used to create a new state based on the existing state and the current action. It returns the newly created state. For example, in add item scenario, it creates a new item list and merges the item from the state and new item and returns the newly created list. 
	Line 4568: Here, dispatch refers the dispatch object used to dispatch action in the redux store and Object refers one or more dispatch functions as props of the component. 
	Line 5150: TransitionGroup is a container component, which manages multiple transition component in a list. For example, while each item in a list use CSSTransition, TransitionGroup can be used to group all the item for proper animation. 




Line  170: React toolchain helps to create, build, run and deploy the React application. React toolchain basically provides a starter project template with all necessary code to bootstrap the application. 
	Line  225: Babel helps us to write our application in next generation of advanced JavaScript syntax. 
	Line 4526: React redux is an advanced state management library for React. As we learned earlier, React only supports component level state management. In a big and complex application, large number of components are used. React recommends to move the state to the top level component and pass the state to the nested component using properties. It helps to some extent but it becomes complex when the components increases.  
	Line 4527: React redux chips in and helps to maintain state at the application level. React redux allows any component to access the state at any time. Also, it allows any component to change the state of the application at any time. 






Line  243: React library is built on a solid foundation. It is simple, flexible and extensible. As we learned earlier, React is a library to create user interface in a web application. React’s primary purpose is to enable the developer to create user interface using pure JavaScript. Normally, every user interface library introduces a new template language (which we need to learn) to design the user interface and provides an option to write logic, either inside the template or separately.  
	Line  755:   rollup v2.36.1 bundles src/index.js → dist\index.js... LiveReload enabled 
	Line  854: As we learned earlier, React JSX is an extension to JavaScript. It enables developer to create virtual DOM using XML syntax. It compiles down to pure JavaScript 
	Line  930: •Properties - Enables the component to receive input. 
	Line  932: •Events - Enable the component to manage DOM events and end-user interaction. 
	Line  934: •State - Enable the component to stay stateful. Stateful component updates its UI with respect to its state. 
	Line 1168: React enables developers to create dynamic and advanced component using properties. Every component can have attributes similar to HTML attributes and each attribute’s value can be accessed inside the component using properties (props). 
	Line 1679: Event management is one of the important features in a web application. It enables the user to interact with the application. React support all events available in a web application. React event handling is very similar to DOM events with little changes. Let us learn how to handle events in a React application in this chapter. 
	Line 2263: React introduces an entirely new concepts called React Hooks from React 16.8. Even though, it is a relatively new concept, it enables React functional component to have its own state and life-cycle. Also, React Hooks enables functional component to use many of the feature not available earlier. Let us see how to do state management in a functional component using React Hooks in this chapter. 
	Line 2808: One of the advanced features of React is that it allows arbitrary user interface (UI) content to be passed into the component using properties. As compared to React’s special children property, which allows only a single user interface content to be passed into the component, this option enables multiple UI content to be passed into the component. This option can be seen as an extension of children property. One of the use cases of this option is to layout the user interface of a component.  
	Line 3396: Http client programming enables the application to connect and fetch data from http server through JavaScript. It reduces the data transfer between client and server as it fetches only the required data instead of the whole design and subsequently improves the network speed. It improves the user experience and becomes an indispensable feature of every modern web application.  
	Line 4308: Here, WithRouter enables ArticleList component to access the tag information through props. 
	Line 4452: Next, create a file, App.js under src/components folder and start editing. The purpose of the App component is to handle all the screen in one component. It will configure routing and enable navigation to all other components. 
	Line 4882: •Used Provider component from React redux library and set the store as props, which enables all the nested component to connect to store using connect api. 
	Line 5297: By default, profiling option is disable and can be enabled through –profile command line option. –profile will include profiling information in the code. The profiling information can be used along with React DevTools to analyse the application. 
