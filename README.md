# Ravenous

## My 1st React.js project from Codecademy

### Part 1: First Commit - Mar 1, 2020

This is my first React.js project from my [Create a Front-End App with React](https://www.codecademy.com/learn/paths/build-web-apps-with-react), Section 5, Introduction to React that I am building on my computer and pushing to GitHub. I am using VS Code as my IDE. The following are the instructions I am following from Codecademy's website:

### Create Project & Components

Welcome to the first installment of the Ravenous project! Over the next couple of weeks, you’ll build a website called “Ravenous”, a Yelp-like clone.

In total, there will be four parts to this project:

  * Creating Static Components
  * Passing Information to Components
  * Setting the State of Ravenous Components
  * Interacting with the Yelp API
  
Today, you will start by building the first part of Ravenous: 
### Creating Static Components.

Here’s a quick overview of how Ravenous should function:

 * As a user, I should be able to search for restaurants
 * As a user, I should be able to view a list of restaurants returned by the Yelp API
 * As a user, I should be able to sort through restaurants using a filter
 
The four projects will test your knowledge of JavaScript and React, all with the goal of building a Yelp-like clone. If you want to get a feel for what Ravenous can be, visit the Yelp website and search for restuarants in your area.

Finally, a few notes before getting started:

 * In each project, you’ll be presented with the intended, final outcome (of that project) in the Codecademy browser component.
 * You should expect to spend more than 1 day on this specific project. It’s the base of the entire app, and it will likely take a few days to complete this project. It’s OK if it is not all finished in one day.
 * If you don’t understand how to implement a certain part of the project, we’ll provide guidance as needed. However, you should expect to search Codecademy for the exercises that will provide you with the relevant information.
 * You should expect to complete all four Ravenous projects on your personal computer using your preferred tools (terminal, text editors, etc.).
 
### Part 1 Instructions:

### Create a React App

- [x] **1.** Start by creating a React app using the `create-react-app` package in your preferred terminal. The name of your app should be `ravenous`.

- [x] **2.** In another terminal window, `cd` into the `Ravenous` directory and type the following command: 

      `npm start`

     This command will start a development server and open up a preview of your app in a browser tab. As you build, the preview will automatically update when you save your work. This is a great way of seeing your progress in real-time.

- [x] **3.** Replace the current favicon located at **public/favicon.ico** with [this icon](https://s3.amazonaws.com/codecademy-content/programs/react/ravenous/ravenous_favicon.ico). Make sure you save the new image as **favicon.ico**.

### Add a CSS Reset

- [x] **4.** By default, `create-react-app` will generate a sample application. We’ll need to add a reset.css file to ensure our app is styled the same in every browser.

     `cd` into the newly created `Ravenous` directory. Take a look at the default folder structure generated by `create-react-app`. Use the command line to create a new file called **reset.css** in the **public/** directory. Copy and paste [this CSS](https://s3.amazonaws.com/codecademy-content/programs/react/ravenous/reset.css) into **reset.css**.
     
     
### Part 2 Instructions:

### Passing Information

Welcome to the second part of the Ravenous project! Take a minute to review what you accomplished in the first part of this project. You:

 * Used `create-react-app` to start your project
 * Built all of the components you’ll need for the remainder of the project
 * Simulated what Ravenous should look like after returning search results
 
In this project, you’ll complete the second part of Ravenous: **Passing Information to Components**.

So far, you’ve hard coded business information and rendered it manually. Now we’ll focus on how information (like business information) can pass from component to component with less hard coding. This is crucial as we build towards the goal of constructing a Yelp-like clone.

A few notes before getting started:

 * You should expect to spend more than 1 day on this specific project. It’s OK if it is not all finished in one day.
 * If you don’t understand how to implement a certain part of the project, we’ll provide guidance as needed. However, you should expect to search Codecademy for the exercises that will provide you with the relevant information.
 
- [x] **1.** Future parts of this project will implement the Yelp API. That specific functionality will require that you pass information from the Yelp API to multiple components. In this project, you’ll build the initial portions that will set your project up for this functionality in the future.

- [x] **2.** In another terminal window, `cd` into the `Ravenous` directory and type the following command:

     `npm start`
     
     This command will start a development server and open up a preview of your app in a browser tab. As you build, the preview will automatically update when you save your work. This is a great way of seeing your progress in real-time.

### Create businesses Array

- [x] **3.** When the Yelp API is implemented, a list of businesses will be returned to **App.js**. Therefore, we should create a hard-coded list of businesses there and then pass them to the appropriate components.

     Open **Business.js**. Cut the entire `business` object and paste it into **App.js**.

     Make sure to paste it right after the imports and above the `App` class declaration.
     
- [x] **4.** Take a look at **BusinessList.js**. What do you notice about the contents of the `BusinessList` div?

     There’s a lot of repetition here. Specifically, `the <Business />` component is repeated six times. Recall that we manually did this in the `BusinessList` component so that we can simulate a list of returned business. We’ll refactor this to remove some of the component repetition.
     
     Go back to **App.js**. Under the `business` object, create a `businesses` array. The array should hold six references to the `business` object.





