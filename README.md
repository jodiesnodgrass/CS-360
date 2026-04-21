# CS-360

Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

The requirements for the app I developed included creating an account, inputting goal weight and daily weight, and if desired granting permission for SMS notifications. The goal of the app was for users to keep track of their daily weights. Tracking a daily weight and seeing progress through a timeline in the table would keep the users motivated to loosing weight and using the app. 

What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

My app included three main UI screens. Only one additional screen is seen when a user is creating an account. The first screen is user login or creation. The next screen is the table where the user can input current weight and goal weight and the date auto populates once information is added to the database displaying in the table. The next screen is sms permission which the user can go to that page if they want or advoid it all together. With the three simple screens the app is not complicated for the user to use on a daily basis. 

How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?

The app I developed is a persistent Android application built with the Room Persistence Library and SQLite designed to manage user authentication and health data. It features a complete CRUD (Create, Read, Update, Delete) interface where users can log daily weights and view progress in a dynamic responsive grid. The app also includes a smart SMS Notification system that triggers alerts when goal weights are reached featuring graceful handling of Android system permissions. CRUD and permissions are very helpful techniques to know for any future projects. 

How did you test to ensure your code was functional? Why is this process important, and what did it reveal?

With every change in code I ran the app in the medium phone emulator to test functionality. If I waiting to test till everything was complete I could have recieved multiple errors and then would have to determine which file and section has the error. With fixing multiple errors at once it would be like recreating the app which could become frustrating.

Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?

From plan to finalization I only had to figure out one major challenge. The challenge was taking my simple xml and java files and adding databases to the project. I had two add 3 new java files and one new interface to turn my project fully functional and not a simple display.

In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

This was my very first app created! Once I added the databases I was able to show my experience with CRUD. CRUD was seen on the WeightTracker screen with being able to create a new entry, read the entry on the table once added, update weight by 0.5 lbs if needed, and the X on the table to delete an entry.

