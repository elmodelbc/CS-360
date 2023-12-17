# CS-360

Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

This app was designed to allow an organization the ability to manage their warehouse inventory.  The application stores users, permissions, and stock items in an SQLite database.  The application allows a user to create an account, with a specific role, to manage warehouse inventory items.  The roles include creating, reading, updating, and deleting (CRUD).

What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

The application includes a login screen, an inventory screen, a new user screen, an item update screen, an item delete screen, and an item create screen.  The UI design keeps users in mind because it performs well and has a straightforward simple approach.  The design was successful as the application does exactly what was requested without any additional features that take away from the overall UI design.

How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?

I coded the application by adding one feature at a time and thoroughly testing that feature before moving on to the next requirement.  I used the techniques and strategies from the Android Best Practices guide.  All features are simple, perform well, and keep the user in mind.  The UI is consistent and uses neutral colors and only the required features to achieve the purpose of the application.  These strategies and processes can be used in the future the same way they were applied to this project.  Code one requirement at a time, test, make code corrections, test, and move on to the next requirement.

How did you test to ensure your code was functional? Why is this process important and what did it reveal?

I tested the code using Android Studio and AVD Manager.  This process was important to test successfully test the code and it revealed the importance of developing code that supported multiple form factors and APIs to make the application as compatible as possible with the broadest range of devices.

Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?

The biggest challenge was reading data from the SQLite database and then searching or performing an action or function based on the returned data.  Multiple logic branches were required to perform the right function once the data was returned from the db.

In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

I think I was particularly successful when it was necessary to develop functions and methods to take the necessary actions and change the state of the instance members.
