## Getting started with react!

### **Theory:**

### **Getting started:**
- Came in 2013 by Facebook.
- Library not a framework used to build UI very faster.
- Used in building single page application. Single page application means whole page doesn't load for small change, only the part which has changes reloads.
- Can be used with CDN also but npm is the standard way of using React because it assists in managing packages, minifies the project in single file which is very helpful in production.

### **Folder structure breakdown:**
	1. package.json saves our application details like project name, version of project and react, commands, all additional installed packages.
	
	2.  package-lock.json is expansion for package.json. It has all details of package.json. It stores details of node modules in the form of tree structure.
	
	3. .gitignore has nothing to do with react or node. It is related to git. We never commit node modules so this is how we avoid it; by writing that in this file.
	
	
	4. src where all our code is present.
	
	5. src/App.js : We start writing code from here.
	
	6. src/App.test.js : All unit test cases are written inside this. We run test cases from cmd which reduces loads of testers.  
	
	7. index.js is react entry point.
	
	8. reportWebVitals.js returns performance report. We will find it embedded at the last of index.js.
	
	9. setupTests.js has all the setup for test cases.
	
	10. public folder contains HTML kind of details like favicons which are not related to react.
	
	11. public/index.html has a div with root, src/index.js searches for this root and sticks the react code inside that root div.
	
	12. manisfest.json is called as metafiles. It contains icons, themes. It is used when we build progressive web apps. It is not based on basic level. We can also delete this.
	
	13. robots.txt is to protect project from Google search engine. We can delete this also.
	
	14. node-modules. It's like C drive of our project. Surprisingly it contains react-js, react-dom also. We can see index of these packages from both the json files. We don't touch it. Whenever we do npm install, this node modules are recreated and old one will be deleted. We don't code in public file also. We only code in src.
	
	15. build folder is built when we make build. It has 2 to 3 files.
	
	



### **Components in React:**
 - **Functions!** Write once. use as and when needed. 
 - Visual wise, part of a bigger whole.
 - Inside these functions, we have our HTML elements!
 - We can use have components inside components but using the inner component is tedius, first we need to use/access outer component then inner.
 - Components in react: Simple function and return inside it, inside return Simple HTML. Visualisation point!
 - HTML must be wrapped inside single div.

 ### **Class components in React:**
 - Class > render > return > HTML code.
 - HTML must be wrapped inside single div.

### **JSX:**
 - To write HTML and JS together.

### **Click event and function**
-  We write function name inside braces not write function call statement inside braces.

### **State**
- Component doesn't re-render in case of variables that's why we use State. React is designed in such a way.
- State is a container, just like variable, to be more precise, they are like user defined data type i.e. Object.
- To use state we use useState hook. 
- We need to import React and useState both when we use state.


### **Prop**
- Prop is short form of properties.
- For understanding purpose, prop is just like parameter. Prop & Component = Parameter and function.
- We can change the prop in the component in which we are receiving it.

### **Show Hide field based on button click**


