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
