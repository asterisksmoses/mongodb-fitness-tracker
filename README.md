Fitness Tracker

Table of Contents

- Description
- How to Use
- How to Install

Desription

This project builds a workout tracker with Express.js and MongoDB. User can start a workout plan and each plan can track multiple exercises. This application tracks two type of exercises: resistance and cardio. For resistance, the application tracks weight, reps, sets. For cardio exercises, it tracks ditances. After all, the duration of every exercises will be tracked as well. User can see the summary for their current workout plan at the main mage. If user wants more detailed data, he/she can view dashboard for detailed graphs and distributions of exercises performed over the last 7 workout plans.

Technologies Used

- MongoDB
- Mongoose
- Express.js
- Node.js
- RESTful Api
- Chart.js
- HTML 5
- CSS 3
- JavaScript
- VS Code

How To Utilise This Tool

This application helps user track different exercises under the same workout plan. Exercises are categoried into two major groups: cardio and resistance. There are four main features: adding cardio, adding resistance, viewing summary of current workoutplan, exploring data dashboard for past 7 workout plans.

Feature: Adding a New Cardio Exercise

To add a new cardio exercise, user need to enter the name of the exercise, distance in miles and its duration.

Feature: Adding a New Resistance Exercise

To add a new resistance exercise, user need to enter the name of the exercise, weights, setss, reps, and its duration.

Feature: Summary of Current Workout Plan(s)

The summary is automatically generated upon launching or returning to homepage (by clicking on `Fitness Tracker` on the top left corner).

Feature: Dashboard of Last 7 Workout Plans

By clicking on `Dashboard` on the top left corner, user will be taken to a dashboard for different statistics for last 7 workout plans.

How to Install/Use

To be able to use this application locally, you need MongoDB community server installed. Type this command in command-line to check:

```bash
mongo --version
```

Once you have MongoDB installed, install the require packages, you will need mongoose to use the seed function, use the following command:

```bash
npm install
```

The last step would be seeding, use this command:

```bash
npm run seed
```

To initialize the server, type this command in console, then use the application through brower.

```bash
npm start
```


Author Info

Moses Gitonga is software engineering student at ALX AFRICA from Kenya, living in Nairobi Area. If you have any questions, email him at asterisksmoses@gmail.com or visit his github https://github.com/asterisksmoses
