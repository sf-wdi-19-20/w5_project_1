# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) SF WDI 19/20 - Project One

## @TODO

Combine timelines

assign groups (first letter)




## DESCRIPTION

It's time to put everything that you've learned in the past month together! For the first project you will use your knowledge of front and back-end web development to produce an awesome web application that can be used by friends, family or any of the other billions of people who use the Internet. The type of web application you create is your choice.

**The objective of this project is to:**

* Apply the skills you've learned by building a web application from the ground up.
* Demonstrate mastery of topics covered during this course so far.

You will each need to turn in an individual project, but you will move faster and learn more if you take time to pair program with other students.

## CORE REQUIREMENTS

**Your app should have all of the following:**

* **Express API** Implement a server-side JSON API with Express.
* **RESTful Routes** Design the routes in a <a href="http://restfulrouting.com/mappings/resources" target="_blank">RESTful</a> manner.
* **MongoDB** Persist at least two models in a Mongo Database.
* **AJAX** Leverage your server-side API to fetch JSON asynchronously to the client-side.
* **jQuery** Use jQuery to manipulate the DOM and/or data on the client-side.
* **Templating** Render the JSON data on the client-side using underscore templates.
* **Testing** Write request tests for 50% of your app's API routes.
* **Authentication** Enable users to sign up, log in, and log out.
* **Data Validation** Validate data by handling incorrect inputs during sign up, such as unique email addresses and minimum password lengths.
* **Model Relationship** Create a `has_many` relationship between the User and another model using either embedded or referenced data.
* **Visual Design** Use Bootstrap to kick-start your UI and UX.
* **Heroku** Deploy your app to Heroku.
	* Ensure no app secrets are exposed. __Do not commit secret keys to Github!__


## BONUS CHALLENGES

If you want to push yourself and learn something new, optionally consider doing some of the following with your app, but *please talk to an instructor* beforehand:

* **Authorization** Disallow users from deleting content in other user's profiles. This means a user should not be able to delete a post (or other resource) if it is not theirs.
* **Many-to-Many** Set up a many-to-many relationship like "tags" on posts.
* **Search** Build a form that allows users to search for data based on keywords.
* **Email** Send emails with express-mailer
* **SMS** Send SMSs with the Twillio API
* **Payments** Add payments with stripe.com
* **External API** Use an external API to integrate rich data into your app.
* **Web-Scraping** Write a web-scraper to collect data from a website that doesn't have an API. Example technologies include <a href="http://casperjs.org" target="_blank">Casper</a> or <a href="https://www.kimonolabs.com" target="_blank">Kimono</a>.
* **Web Sockets** Create an open, real-time connection between your server and client (e.g. live chatting). Check out <a href="http://socket.io/" target="_blank">Socket.io</a> if you're interested in web sockets.
* **Whatever else you can think of!**

## TIMELINE (OUTSIDE-IN)

Thursday

	- Brainstorm Purpse or Idea
	- Write User Narratives
	- Draw Wireframes
	- Draw Schema Drawing

Weekend

	- Build initial index template of core resource (e.g. "Post", or "Article", or "Todo")
	- Send array of static data to it from scripts.js (add jQuery)
	- Move array of static data to server (build server with 1 route)
	- Move array of static data to DB (add mongoose and seed local DB)

Monday

	- Deploy index template with api and db connection to Heroku
	- Build form template and POST route
	- Push to Heroku

Tuesday

	- Build signup template
	- Add User model and Signup route to server
	- Build login template
	- Add login route to server
	- Push to Heroku

Wednesday

	- Add another resource or a "reach" feature
	- Push to Heroku

Thursday

	- Improve and customize styling
	- Final Push to Heroku

## TIMELINE

* **Thursday, July 16th** - Submit your project proposal to an instructor and make a Kaban board for it using Trello [board](https://trello.com/b/dl7VicOR/sfwdi18-project1). Be ready to talk about the scope of your project. Before beginning work on your project, your project idea and the scope of your project must be checked-off by an instructor. [More on that here](@TODO). You will need the following for an instructor check-off:
    * Wireframes
    * User stories
    * Models and DB design
* **Monday, July 20th** - Deploy your code to Heroku by the end of the day. It is not important how much coding you have done at this point; deploy whatever you have.  This will make your life easier. We will have a workshop on Monday afternoon on deploying to Heroku with Mongo.
* **Friday, July 24th, 9:17am** - Project due and presentations!

## PLANNING

####Before you start coding...

* **Getting Ideas** Think about problems you know of - things that suck or are broken in the world. Could you build something that could grow into a solution? Try to do one thing well and then iterate.
* **User stories** Outline your core user stories and divide them into sub-stories. Use your own [Trello](https://trello.com/) board to track your progress and keep you focused.
* **Wireframes** Sketch out what a your core pages will look like and how they will work.
* **Object Models** Use an entity relationship diagram to plan out the Models, their relationship(s), and properties.

*DO NOT start coding before each of the above is clearly outlined and approved by an instructor.*

* **REMEMBER to build "outside-in"**
 starting with an index template with static data, then swap in dynamic data stored on the client, then swap in getting the data with a GET call to a URL route on your server for the data, then saving the data in your database.

## WHAT WE ARE LOOKING FOR
####Code should be...

* Commented
* Modular
* DRY
* Frequently committed, with descriptive commit messages
* Properly indented

####Workflow should be...

* Strategic —
*Were you mindful about balancing your own resourcefulness with seeking help when necessary?*
*Did you think through logical units and plan (e.g., in comments) before starting to code?*

* Documented —
*Did you create a project README, illustrate wireframes, write user stories, draw an entity relationship diagram, etc?*

* Defendable —
*Can you defend why you chose a certain technology or why you implemented your solution in a certain way as opposed to the other options?*

## ACCESS TO INSTRUCTORS
We will a schedule for 1:1s throughout the week. We will also do mini lessons on certain topics if we notice that several people are running into the same issues.

##FINAL DELIVERABLES

* Completion of the **core requirements**
* A link to your website **hosted on Heroku**
* A link to your **source code on GitHub**
* A `README.md` file that serves as your **project documentation**
* A **presentation** illustrating:
	* What is your project and what does it do?
	* What was your motivation to build it?
	* What are you proud of?
	* What would you do with more time?
	* What aspect presented the most challenges?

##GROUPS

ADAM:
@TODO


BRIANNA:
@TODO

CAMERON:
@TODO


DEVIN:
@TODO

###HAPPY CODING :)
