# Mock interview

---
This is a pool of questions that technical interviewers can ask applicants.

Note: This pool is not exhaustive and would only cover some of the questions that can be asked.

Programming concepts:
1. What are the four fundamental concepts of OOP? Explain each in your own terms.
2. What is the difference between Agile and Waterfall methodologies?
   a) Waterfall is traditional and starts with an entire prototype and show to end user. Top to bottom when all requirements set in stone. Agile is newer         and usually done in stages and allows changes.
4. Explain Scrum in your own terms. What are the artifacts and rituals related to Scrum?
5. What is the advantage of CI/CD?
   Auto testing and deployment which allows devs to received feedback on failures.
7. What is the difference between encryption and hashing?
   
9. What is XSS and how can it be prevented?
10. Why is version control important?

JS:
1. What is the difference between var, let, and const?
2. What is the syntax of enhanced for loop in JS?
3. What are arrow functions?
4. What is the difference between promise and async/await?
5. What is the difference between import and require?
6. What is the difference between synchronous and asynchronous operation?
7. What is the difference between pass-by-reference and pass-by-value?

Databases:
1. Explain the difference between SQL and NoSQL databases? Give concrete use cases when each can be used.
2. What are the 4 main operations that can be done with databases?
   a) CRUD.
4. Explain the different relationships in a relational database?
   a) 1-to-1 e.g.
   b) 1-to-many e.g. mother to children.
   c) many-to-many e.g. cousins.
5. Explain the concept of ACID for relational databases.
6. What are the different types of NoSQL databases and give some use cases for each.

Backend Services:
1. What is REST architecture and how is it implemented?
2. What can requests contain?
3. What is the difference between PUT and PATCH?
   a) PUT uses REQUEST URI to supply modified version of requested resource. PATCH supplies A SET OF INSTRUCTION to modify the resource.
5. What is an ORM and what is the advantage of using ORMs?
6. Explain the following: Routes, Controllers, Services.
7. What is middleware used for?
   a) Authentication before using services, e.g. e-commerce payment.     

React:
1. What is JSX?
2. What are props and hooks?
3. Why are components used in React?
4. What is the difference between DOM and Virtual DOM?
5. What is a state in the context of React?
6. Explain how Axios can be used to communicate with the backend server.

React Native:
1. What is the difference between React and React Native?
   a) RN is a framework for IOS & Android devices while React is a JS library.
   b) RN does not manipulate the DOM while React does.
   c) RN runs a process that communicates with Native devices via an async bridge.
   
3. How can engines be integrated with React Native?
  a) Through expo install expo-sensors.
  
5. How do you take into account the difference in screen sizes of mobile phones?
  a) By using Dimensions API from RN and useWindowDimensions hook.

