# Theatre Review

This site is for all to use. You can view shows that others have seen and see what they had to say about them. 

For a more interactive experience you can Register and add your own thoughts about your own experiences at the theatre, whether they are in London or your own local theatres.

The site allows users to Create, Read, Update and Delete any shows they have input themselves. They can also read what others have written but cannot alter them in any way.

## UX

![alt text](static/images/screensizes.PNG)

There are so many Theatres throughout the UK that it would be impossible to search each one individually. This site would make that much easier. The search facility will help you look up a show you would like to see and check on other peoples opinions on the show. You could also look for inspiration for something new for you to see.

Visitors to the site can:

* View shows that have been added.
* Read reviews that have been written.
* Search for shows.
* Register an account for free.
* Login (if already registered).
* Logout of my account

Registered members can:

* View shows that have been added.
* Read reviews that have been written.
* Search for shows.
* Login.
* Create new shows they have seen.
* Update or Edit shows they have added.
* Delete shows they have added.

There is also an Admin Login which allows the owner to add, edit or delete genres where necessary.

## User Stories

* As a user I would want a site that is easy to use and navigate round.
* As a user I want to have an aesthetically pleasing site
* As a user I would want a free to register account.
* As a user I would want to see what shows are around.
* As a user I want to be able to register as a member.
* As a user I would like to add my own reviews.
* As a user I would want to be able to update my reviews.
* As a user I would want to be able to delete my reviews.
* As a user I would want to read other peoples reviews.

#### Developer Aims

* As a developer I want to create a visually pleasing site.
* As a developer I want to make a site that is easy to follow.
* As a developer I want to give the user the ability to Create, Read, Update and Delete their own reviews.
* Show an understanding of the Key components used in development, ie MongoDb, Heroku, Python and GitHub.
* As a developer I want the user to be encouraged to interact with the site easily.

#### Site Owners Aim

* As the site owner I would want the user to enjoy using the site and to ask their friends to jin as well
* As the site owner I would hope to learn about more shows myself and be encouraged to go to see them.
* As the site owner I would, eventually, hope to encourage show producers to see the site as a possible way of advertising and therefore make a small income.



## Wireframes

I used Balsamiq for my wireframes and showed each page as a monitor size, a tablet size and a mobile phone size. 

[Link to Wireframe](https://github.com/Craggy19/theatre_reviews/blob/master/static/images/theatre_wireframes.pdf)

## Layout

I chose the background for my site as it shows the inside of a theatre and it gve me the ideas for the colour scheme. 

The colours I used best depicted the theatre and the usual colour of the curtain in front of a stage.

I chose the typography as a warm and fun font that I found on [Google Fonts](https://fonts.google.com/)
I felt it suited the layout of the pages. I used it as the main header for the site and also on the headings of each individual page.

## Images

The Background I used is of Edinburgh Festival Theatre and the image itself was taken from Google images and the actual image came from Time Out magazine. [Background Image.](https://www.timeout.com/edinburgh/theatre/edinburgh-festivals-2015-theatre-reviews)


 # Features

 I feel that this is a straightforward site that is easy to navigate round and the features include

* A visually attractive home page with site information.
* A prompt to either Login or Register.
* Ability to read all reviews without the need to register or log in.
* Easy to register page (and it is free).
* Easy to login page.
* A page that lists all Shows that are currently in the Database. 
* Easy to read details of each show using a drop down facility.
* Search facility for all shows.
* Anyone registered can Create their own review.
* Anyone registered can Update a show they have Created.
* Anyone registered can Delete a show they have Created.
* You can only Delete or Update shows you have Created but other site visitors can read your reviews.


## Features left to Implement

* On future versions I would like to add Images of the shows reviewed, for instance the billboard image and possibly a picture of the theatre from the outside. 
* I would also like to look into the possibility of installing a location map so it will give users an idea of where shows are being performed. 
* Install a marks out of ten for each show 
* From the marks out of ten I would like to create a Top Ten Shows list.


# Technologies Used

* [HTML](https://html.com/). 
    * Used for structure of the site.
* [CSS](https://www.codecademy.com/learn/learn-css). 
    * Used for the styling of the site.
* [Python](https://www.python.org/about/apps/). 
    * Used for Backend programming.
* [JavaScript](https://www.javascript.com/). 
    * Used for functionality of the site like Modals.
* [JQuery](https://jquery.com/). 
    * Adds functionality to Materialize coding like dropdowns.
* [Balsamiq](https://balsamiq.com/). 
    * Used to build wireframes.
* [Materialize](https://materializecss.com/). 
    * Used to add front end components.
* [Font Awesome](https://fontawesome.com/). 
    * All icons used on this site are from Font Awesome.
* [Flask](https://flask.palletsprojects.com/en/1.1.x/). 
    * A microweb framework used with and written in Python.
* [MongoDb](https://www.mongodb.com/). 
    * Database where all shows, users and other info are kept.
* [PyMongo](https://pypi.org/project/pymongo/). 
    * Interacts with Mongodb with Python.
* [Werkzeug](https://pypi.org/project/Werkzeug/). 
    * Used for generating Password security.
* [Heroku](https://dashboard.heroku.com/apps).
    * Used to deploy the website.
* [Google Fonts](https://fonts.google.com/).
    * All fonts are taken from Google Fonts.
* [Google Images](https://images.google.com/imghp?hl=en&gl=ar&gws_rd=ssl).
    * Background image taken from Google Images.
* [Jinja](https://jinja.palletsprojects.com/en/2.11.x/).
    * A templating language for Python.
* [GitHub](https://github.com/).
    * Used as a repository for this site.
* [Git](https://git-scm.com/).
    * Version Control

    
            
 # Testing

I have set up and tested all components of the site from the Navbar down. The Navbar changes from a vertical list on large screens down to a burger icon on smaller screens.

The Navbar lists change depending on if the user is logged in or not. These have all been tested without a problem.

#### If user is not logged in:

Navbar will show 
* Home.
* Shows.
* Log In.
* Register. 


#### If user is logged in:

Navbar will show
* Home.
* Shows.
* Add Shows.
* Log Out.


---

### **Home Page**

**As a new unregistered user.**

All navbar options were tested to check the correct navigation. Within the page there is a brief description
of the site which also contains the buttons Log In and Register. These buttons have also been tested for correct navigation. 

**As a user that has logged in successfully**

The navbar options are different and also checked for correct navigation. Inside the brief site description now
is an option to view all the Shows that have been reviewed. This button has also been tested. 

---

### **Register Page**

Navbar tested and all links work correctly. Input works for Username and Password, Register button takes you to a profile page stating Registration successful
and shows that no results are found, this is because the new user hasn't reviewed any shows currently. 
The page also has a button to add a show review, which will tale you to the Add Show Page,
or to search for shows in the database. The reset button will take you to the shows page with all reviewed content.
Finally there is a button with "Already Registered? Log In Here" option which will take you to the Login Page.
If you input a username, that has already been used, there will be a pop up stating "Username already exists".

---

### **LogIn Page**

Navbar tested and all links work correctly. Input for username and password are filled out and Log In button takes you to a shows page with all the shows you have currently reviewed under that login. 
There is also a banner welcoming the user to the site. The reset button will take you to All shows reviewed by you and other members for you to view. The search button works as before on the register page.
If you are not currently a member you have the option to register an account, this button will return you to the Register Page.


---

### **Add Show Page**

Navbar tested and all links work correctly. Adding a show for user to review is simple. The genre section is a dropdown option which should cover most topics. Then just fill in the sections accordingly. Finally hit the Add Show button 
and you will be taken back to the All Shows page with a banner stating "Show Added Successfully"
There is also an option to cancel or clear and start again. All buttons tested without a problem.

---

### **Shows Page**

Navbar tested and all links work correctly. If you are logged in as a member the Shows Page will show a list of all shows and if you added them you will have
the option to edit or delete those shows, you will be able to tell as they will have an edit or delete icon next to the show name. If others have added them you will not have this option.
If you wish to delete your review click on the bin icon and a modal will pop up to confirm your request. If you click on the edit icon you will be taken to the Edit Show screen which you can then
change whatever you need to and then submit. This will have a pop up saying "Show Updated Successfully".
The search area allows you to look up either a show name or a writers name. If no name or show is found a pop up stating "No Results Found". Just reset and try again.
If you click on the individual show it will dropdown to show the deatils of that show. 
All these buttons have been tested and work as expected.

---

### **Admin Page**

There is an Admin Page that is only available if logged in as Admin. This has the ability to Add, Edit or Delete genres of shows.
All these buttons have been tested accordingly.

---

## **Friends and colleagues testing**

I sent my link to friends and colleagues to test and generally I received good feedback. 
The main (minor) issues were aesthetic and were soon resolved, these included colour scheme changes on Modals and pop up messages.
Another issue was the spacing on some of the buttons needed to be increased. this was changed accordingly. 

---

# BUGS

During the process one or two bugs came about.
* When putting in a pop up I had an error stating the Cursor len was incorrect. I spoke to my mentor and he suggested a different Jinja code and this solved my issue. 
Instead of using

{% if shows|length > 0 %}

{% endif %}

I just used 

{% for show in shows %}

  {# my code here #}

{% else %}
  <p>Sorry, no results found</p>
{% endfor %}

This then worked as expected.

* Another bug was on screen sizes. My header title was always to large for small size screens like mobiles. 
I adjusted the sizes in CSS to fit accordingly. It works perfectly on my iphone and also on the inspect section for phones and tablets

* Most of the default font colours needed to be altered to fit with my colour sceme for the website.

* Once I was nearing completion for the site and was looking through I realised that the profile page I had designed was quite unnecessary, this was confirmed by my mentor 
and therefore I decided to delete it and carry on without. 

--- 
