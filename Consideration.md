                          The Design Process
                          
1) In this project we need to create database at the entry i.e during signup process, I will have to store the signup information somewhere so                               that I can compare it later when the user logins.
2) When the login id and passward entered is equal to the details when signup info then the submit button will lead to another page where we can see 
   the list of sessions with start and end date.
3) Clicking on any cource will lead to another page where any student can register themself and check the max strength of the session.
4) Registering in each page will lead to another page where some details from students will be taken and stored into the database using mongodb and nodejs.
5) After registering inside the registered cource will allow the student to continue forward with attending the session.


                         Security Considerations
1) Software being up to date.
2) Strong Passward Policy.
3) Backing all the data that has been collected till date.
4) Encrypting Login Pages.


                         Tech Decisions
1)Maintainability:= Creating a database table with a set of options. The impact of a change would be much lower and may not require a new build and deployment. However,                      the upfront cost of developing a new table in the database and managing the asset will take time and resources. And for this reason, it is easy to                         go with the hardcoding option, despite the drawbacks. This creates a tech debt.

2)Readability:= Complexity of words and sentence structure is easy to understand and run.

3)Scalability:= Handling increased traffic and loads on website.Maintaining user experience.Using the right frameworks that support asynchronous programming, database                   optimization, loose coupling, partitioning and caching to maintain app performance as you grow your user base. These frameworks include Node.js,                          AngularJS, among several others.
