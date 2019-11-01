# express-locallibrary-tutorial
https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs

The purpose of this project was to learn how to use Node.js in conjunction with NPM and Express to program server-side activity for a website.  Guidance was provided by a tutorial on the Mozilla website--a link to it is above.

The earlier two-thirds of the tutorial were pretty straight-forward.  The greatest challenges I had were in the challenge portion of part 6 and the deployment portion of part 7.  In the former, my issues came down to making sure that the names referring to various objects, functions and variables were consistent in and between .js files--a task which becomes progressively more difficult as both the size of the entire program and the number of variables, functions and objects in the program increase.  In the case of the latter, my attempts to link to a separate 'production' database, both in the app.js file and as a config variable (MONGODB_URI) in Heroku were consistently met with a H12, or request timeout error.  The same happened when both were set to the database used when building this program.  With some experimentation, I found the MONGODB_URI config variable in the Heroku app to be unnecessary and the app worked fine without it.

In reflecting, I find Mozilla's tutorial would be an effective "next step" in learning how to program server-side.  The method used by the tutorial does provide a great deal of "hand-holding" sans the challenges, which is meant to assist those who have never done server-side programming before. However, it condenses so much in seven parts that I think a whole bunch of smaller exercises to teach concepts one-at-a-time would be more effective for first-time server-side programmers, before proceeding to a tutorial like Mozilla's to apply what they learned.  
