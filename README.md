# Retro Console 

## Milestone 4 Project

Retro Console - my fourth milestone project - an e-commerce site for the sale of retro consoles from the ages.
## [Link to finished site](https://retro-console-ms4.herokuapp.com/)

A site to purchase retro gaming consoles and accessories.

NNEEEEEEED CHANGING        <img src="/media/screen-mockup.png" alt="Images of site on different media screens."/>

#### A view of how the site looks over different media.
---
# Table of contents

- [UX](#ux)
    - [Website owner business goals](#website-owner-business-goals)
    - [User goals](#user-goals)
        - [As a site owner](#as-a-site-owner)
        - [As a visitor to the site](#as-a-visitor-to-the-site)
    - [Structure of the website](#structure-of-the-website)
    - [Wireframes](#wireframes)
    - [Surface](#surface)
- [Features](#features)
- [Technology](#technology)
- [Testing](#testing)
    - [Code Validation](#code-validation)
    - [Functionality testing](#functionality-testing)
    - [Compatibility testing](#compatibility-testing)
    - [User stories testing](#user-stories-testing)
    - [Issues found during site development](#issues-found-during-site-development)
    - [Performance testing](#performance-testing)
    - [Known bugs](#known-bugs)
- [Deployment](#deployment)
- [Credits](#credits)
- [Screenshots](#screenshots)

---
## UX


## User goals

## Website owner business goals

To create an easy to use visually appealing site where book lovers can see and leave reviews.


## User stories

### As a site owner
* I would like the site to be easy to navigate.
* I would like the ability to add/delete/edit products with admin abilities.
* I would like to be able to order products by price. High-low and low-high.
* I would like to be able to filter my products by brand.
* I would like to receive feedback from visitors to my site so I can keep improving my offering.
* I would like visitors to be able to register via a login to my site to promote repeat business.
* I would like to have an email facility to let customers know that their order has gone through.
* I would like to provide a secure payment facility for the customer.


### As a visitor to the site
* I would like the site to be easy to navigate.
* I would like to clearly see what products are available and how much they cost.
* I would like to register and log in to keep a list of purchases that I have made and to speed up checkout.
* I would like to be able to check products by brand.
* I would like to be able to contact the site with any queries


## Structure of the website

I have tried to make a website that is easy to access, and that has similar visuals/colour themes throughout. 
It should be fully accessible on a range of devices and simple to navigate for all.
The website will consist of eight data models, login and register functions and the ability for admin to add/edit products. There will be the ability for the user to look by decade, manufacturer, price, category and name. The user will also be able to change their delivery details and view previous purchases.
I have asked some friends and family for their input and to test interaction

## Wireframes

I used the site https://www.balsamiq.com/wireframes/ to create the wireframes for the site.

## DB Schema

I used the site https://app.diagrams.net to create the db schema for the site.

<img src="/media/db_schema.png" alt="DB Schema of site."/>


## Surface

### Colors
Main colours used in a project:
* background: #white with #black text for a clean and crisp visual.
* navbar: #white with #black text with the exception of the logo that was red and blue.
* home page has a hero image of Super Mario and Luigi



### Fonts 

* The Lato font is the main font used throughout the whole website with Serif as the fallback font in case for any reason the font isn't being imported into the site correctly. Lato is a clean and clear and stylish font, so it is both attractive and appropriate. 

___

# Features

The website consists of several pages. The Login, Register, Shopping Bag, Multiple Product pages depending on what filters are selcted, Contact and Home page. Any user also has search facilities to view for specific keywords of products on the site.

A registered user can update delivery information and view their previous purchases from the site.

An Administrator can do all of the above but also has the authority to add/remove/edit products on the site.

Future features may include running polls with authorised users to help determine what other products to sell on the site. 

* Responsive on all device sizes
* Interactive elements

The website has below features: 


[Back to Table of contents](#table-of-contents)


# Technology

### Languages and Frameworks Used
* HTML5
* CSS
* Javascript
* Django
* jQuery
* Font Awesome
* Heroku
* Bootstrap
* Google Fonts
* AWS
* Stripe


### Frameworks, Libraries & Programs Used
1. Google Fonts:
    * Google fonts were used to import the 'Lato' font into the style.css file which is used on all pages throughout the project.
2. jQuery:
    * jQuery to make the navbar responsive.
3. Git
    * Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
4. GitHub:
    * GitHub is used to store the projects code after being pushed from Git.
5. Heroku:
    * Heroku was used to deploy the project.
6. Balsamiq:
    * Balsamiq was used to create the wireframes for the project.
7. Font-Awesome:
    * Font-Awesome was used ifor the icons throughout the website.
8. Lighthouse:
    * Used to test responsiveness of site
9. Webformatter:
    * Used to test my HTML, CSS and JavaScript to ensure there were no errors.
10. JSHint:
    * Used to test my JS to ensure there were no errors.
11. PEP8 Online:
    * Used to check my Python was PEP8 compliant.
12. AWS:
    * IAM and S3 packages setup for user access and storage.
13. Stripe:
    * Payment processing software.
14. Django Allauth:
    * Integrated set of Django applications addressing authentication, registration, account management as well as 3rd party (social) account authentication.


[Back to Table of contents](#table-of-contents)
___

# Testing

## Code validation
The Webformatter.com Markup Validator were used to validate every page of the project to ensure there were no syntax errors in the project for both HTML and CSS.

* [HTML, CSS and JavaScript code checked through HTML/CSS/Javascript Formatter](https://webformatter.com/html) No issues found
* [Python code checked through PEP8 Online Formatter](http://pep8online.com/checkresult) No issues found

## Functionality testing 

 I used Chrome developer tools throughout the project for testing and solving problems with responsiveness and style issues.


## Compatibility testing
 Site was tested across several virtual mobile devices and browsers.

 I tested on hardware devices such as: iPad pro, Macbook, Windows Desktop and iPhone11.


## User stories testing

### As a site owner:

- I would like the site to be easy to navigate.
    * The site is simple to navigate.
- I would like the ability to add/delete/edit products with admin abilities.
    * User with administration rights can add/delete/edit products when standard users can not.
- I would like to be able to order products by price. High-low and low-high.
    * Filters have been added so users can see by price, name, rating or category.
- I would like to be able to filter my products by brand.
    * A manufacturers page with filter has been added to site.
- I would like to receive feedback from visitors to my site so I can keep improving my offering.
    * A contact form is available for users to contact the site.
- I would like visitors to be able to register via a login to my site to promote repeat business.
    * Users can register and are able to login to the site to help repeat business. They can also see what they have previously ordered.
- I would like to have an email facility to let customers know that their order has gone through.
    * There is an email confirmation to let customers know when their purchase has been completed.
- I would like to provide a secure payment facility for the customer.
    * Secure payment is set up through Stripe.


### As a visitor:

- I would like the site to be easy to navigate.
    * The site is easy to navigate.
- I would like to clearly see what products are available and how much they cost.
    * Visitors to the site can clearly see the product image and price.
- I would like to register and log in to keep a list of purchases that I have made and to speed up checkout.
    * Users can register and are able to login to the site to help repeat business. They can also see what they have previously ordered.
- I would like to be able to check products by brand.
    * A manufacturers page with filter has been added to site. There has also been a page created so the user can see products by decade of release.
- I would like to be able to contact the site with any queries
    * A contact form is available for users to contact the site.


---
## Issues found during site development

* The Amazon link is not diverting to Amazon but instead opens up a duplicate of the current page.

* The Website was tested on Google Chrome, Internet Explorer, Microsoft Edge and Safari browsers.

* The website was viewed on a variety of devices such as Desktop, Laptop, iPhone8, iPad Pro & iPhone11.

* Friends and family members were asked to review the site and documentation to point out any bugs and/or user experience issues.

* I had problems when first importing json files over to Heroku where the products would not show up. After googling, using Slack and tutor support I decided to revert back to a previous commit where I knew it to be working and started afresh. No issues second time around.

* New users could not register to site. A server error 500 was reported when they tried. With help from Alan at tutor support I found that  had a typo in my saved email settings in Heroku variables. Once this was ammended it worked fine.

* I had an issue moving my static files over to AWS. Again, with tutor support I managed to get them over by adding the database url to the Heroku variables.



## Performance testing

I ran [Lighthouse](https://developers.google.com/web/tools/lighthouse/) tool to check performance of the website.
Screenshots are presented below:

<img src="/media/lighthouse_homepage.png" alt="Home image of performance from Lighthouse."/>
<img src="/media/lighthouse_product.png" alt="Product image of performance from Lighthouse."/>

I would look to improve on this further down the line and look at having smaller images to help with the performance.


### Known bugs

The navbar spills down to two rows on smaller mobile devices. 

<img src="/media/navbar_bug.png" alt="Bug with the navbar visual"/>

I will look into rectifying this in a later edition.

---

# Deployment

This project was made using GitHub and GitPod. And hosted using Heroku.

## Hosting

1. Created a new repository within GitHub.
2. Opened repository by cloning the repo from GitHub.
3. Created a requirements.txt file by typing `pip3 freeze > requirements.txt` in the terminal which tells Heroku what dependencies are required.
4. Created a Procfile with `web: gunicorn deli_sw.wsgi:application` added to the file.
5. Push the requirements.txt and Procfile to GitHub.
6. Logged in to Heroku and selected "Create New App".
7. Selected the input field "App Name" and gave app a unique name using dashes instead of spaces.
8. Selected the region.
9. Clicked "Create App".
10. Clicked "Resources" and added in Postgres by searching in the search bar.
11. Provisioned a free Hobby Dev database in Postgress.
12. Retrieved the Database URL from the hidden Config Vars in "Settings".
13. Pasted the Database URL in the database path in settings.py and removed the local settings.
14. Run migrations to build the database in Postgres.
14. Loaded the JSON files `python manage.py loaddata <JSON filename>`.
16. Created a superuser with `python manage.py createsuperuser`.
17. Removed the Postgres Database URL so it doesn't end up in version control.
18. Typed `heroku config:set DISABLE_COLLECTSTATIC=1` in the terminal to stop Heroku collecting the static files.
19. Pushed all changes to GitHub.
20. Typed `git push heroku master` to push everything to Heroku.
21. Selected "Deploy" from the Heroku App menu.
22. Selected "GitHub" from the "Deployment Method" section of the page.
23. Ensured my GitHub profile name was showing in the "Connect to GitHub" section and inserted my GitHub repo name in the input field and clicked "Search".
24. Once Heroku had found my repo, I clicked "Connect" to complete the link.
25. Selected "Settings" from the Heroku App menu.
26. Selected "Reveal Config Vars" and inputed the relevant key/value information for the following:

Config Var          

* AWS_SECRET_KEY_ID:
- Obtained when you set up AWS.
* AWS_SECRET_ACCESS_KEY:
- Obtained when you set up AWS
* DATABASE_URL:
- Created when you provisioned Postgres.
* EMAIL_HOST_PASS:
- Obtained from your email provider.
* EMAIL_HOST_USER:
- Your email address
* SECRET_KEY:
- Obtained from [miniwebtool](https://miniwebtool.com/django-secret-key-generator/)
* *STRIPE_PUBIC_KEY:
- Obtained from Stripe
* STRIPE_SECRET_KEY:
- Obtained from Stripe
* STRIPE_WH_SECRET:
- Obtained from Stripe
* USE_AWS:
- True                                                                              |

27. Selected "Deploy" from the Heroku App menu.
28. Scrolled down the page and selected "Enable Automatic Deployment".
29. Selected Master Branch under "Branch Selected".
30. Clicked "Deploy Branch".
31. Once site was deployed, clicked "View" to launch the app and be able to view it within the browser.
32. Heroku will now update everytime you push to GitHub.


[Back to Table of contents](#table-of-contents)

## AWS

An AWS account was setup to store the static css, js and media files.

1. Go to [AWS](aws.amazon.com) and create an account.
2. Once account is created and you are logged in search for S3.
3. Type in a bucket name and select closest region to you.
4. Uncheck Block all public access checkbox and check the aknowledge popup message.
5. Click Create bucket.
6. Click on the Properties tab and enable `Static Website Hosting`. To allow AWS to host our static files.
7. Input `index.html` and `error.html` in the appropriate fields and hit save.
8. Click on the Properties tab and click CORS configuration and add the below before hitting save:
  ```
  [
  {
  "AllowedHeaders": [
  "Authorization"
  ],
  "AllowedMethods": [
  "GET"
  ],
  "AllowedOrigins": [
  "*"
  ],
  "ExposeHeaders": []
  }
  ]
  ```
9. Click the Policy Tab and select Policy Generator which creates a security policy for the bucket.
10. The policy type is S3 Bucket Policy and the Action will be `get object`.
11. Copy the ARN from the bucket and paste it in the ARN field.
12. Click `Add Statement` and then `Generate Policy`.
13. Copy the generated policy in to the Bucket Policy Editor.
14. Add `/*` at the end of the resource key as this will allow access to all resources in the bucket.
15. Click Save.
16. Click the Access Control tab and set the list object permission to everyone under the Public Access section.
17. Search for IAM from the service menu and select this.
18. Create a group with a relevant name.
19. Create an access policy for the group which gives access to the S3 bucket.
20. Click the JSON tab and select import managed policy, search for S3 and select S3 Full Access Policy.
21. Create a user, give them programmatic access and attach it to the group.
22. Download the CSV file, and keep it safe. This icontains the keys required to use AWS.
23. Install boto3 and django-storages using `pip3 install`.
24. Add the keys to the Config Vars in Django.
25. Create a custom_storage file.
26. Run `python manage.py collectstatic` and transfers the static info to AWS.

[Back to Table of contents](#table-of-contents)


## Local Hosting

If you wish to clone my project, feel free. You will need to:
1. Navigate GitHub and find my repository [repository](https://github.com/iainm342/milestone-4).
2. Click the `Code` button next to the Green Gitpod button.
3. Install the modules listed in the requirements.txt file using `python -m pip -r requirements.txt` in the terminal.
4. Install the JSON files using `python manage.py loaddata years`, `python manage.py loaddata manufacturers`, `python manage.py loaddata categories` and `python manage.py loaddata products` in this order as "products" relies on the previous three.
5. Create a SuperUser by using `python manage.py createsuperuser` and follow the onscreen instructions.
6. Run migrations to create your database by using `python manage.py migrate`
7. Create an env.py file in the application folder then add the following:
  ```
  import os

  os.environ.setdefault(
  "SECRET_KEY", "ADD YOUR SECRET KEY HERE"
  )
  os.environ.setdefault(
  "STRIPE_PUBLIC_KEY",
  "ADD YOUR STRIPE PUBLIC KEY HERE,
  )
  os.environ.setdefault(
  "STRIPE_SECRET_KEY",
  "ADD YOUR STRIPE SECRET KEY HERE",
  )
  os.environ.setdefault("STRIPE_WH_SECRET", "ADD YOUR STRIPE WEBHOOK SECRET HERE")

  os.environ.setdefault("EMAIL_HOST_PASS", "ADD YOUR EMAIL HOST PASSWORD HERE")

  os.environ.setdefault("EMAIL_HOST_USER", "ADD YOUR EMAIL HOST USERNAME HERE")

  ```
8. The app can now be run locally by typing python manage.py in the terminal and will be available in your browser using the address `http://127.0.0.1:8000`.

[Back to Table of contents](#table-of-contents)
---


# Credits

### Code
* Code learned through the Code Institute Full Stack Development course was used throughout the site.

* I used the base code learnt through the walkthrough project, Boutique Ado, and used this as a template for my project. This was a huge help in getting the basics of the site. I they added my own custom code to the project.

* Deployment instructions used from GitHub help pages

* Deployment instructions for Heroku used from the Heroku integration page 

* README file template from Code Institute used as a guide. <a href="https://github.com/Code-Institute-Solutions/SampleREADME"></a>


### Content
* All content was written by the developer.

### Links and images and descriptions

IMAGES

NES image main screen - Photo by Tomasz Filipek from Pexels - <a href="https://www.pexels.com/photo/gray-nintendo-nes-console-and-controllers-1637439/"></a>

NES product - Image by <a href="https://pixabay.com/users/robinle-2695228/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=2649705">RobinLe</a> from <a href="https://pixabay.com/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=2649705">Pixabay</a>

controllers image - Photo by <a href="https://unsplash.com/@kike_borland?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Enrique Guzmán Egas</a> on <a href="https://unsplash.com/s/photos/nintendo?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  
SNES controller - Photo by <a href="https://unsplash.com/@pf91_photography?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Patrick</a> on <a href="https://unsplash.com/s/photos/nintendo?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  
Gameboy - Photo by <a href="https://unsplash.com/@helloimnik?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Hello I'm Nik</a> on <a href="https://unsplash.com/s/photos/nintendo?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  
NES controller - Photo by <a href="https://unsplash.com/@ravipalwe?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Ravi Palwe</a> on <a href="https://unsplash.com/s/photos/nintendo?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  
N64 - Photo by <a href="https://unsplash.com/@patsn?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Pat Moin</a> on <a href="https://unsplash.com/s/photos/n64?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  
Gamegear - Photo by <a href="https://unsplash.com/@benofthenorth?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Ben Griffiths</a> on <a href="https://unsplash.com/s/photos/sega?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  
Master System II - Photo by <a href="https://unsplash.com/@helloimnik?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Hello I'm Nik</a> on <a href="https://unsplash.com/s/photos/sega?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  
Megadrive - Photo by <a href="https://unsplash.com/@docs1231?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Joshua Doherty</a> on <a href="https://unsplash.com/s/photos/sega?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  
Dreamcast - Photo by <a href="https://unsplash.com/@usualmorals?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Taylor R</a> on <a href="https://unsplash.com/s/photos/sega?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  
PS1 - Photo by <a href="https://unsplash.com/@helloimnik?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Hello I'm Nik</a> on <a href="https://unsplash.com/s/photos/playstation?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  
PS controller - Photo by <a href="https://unsplash.com/@loravisuals?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">lilzidesigns</a> on <a href="https://unsplash.com/s/photos/playstation-2?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  
PS2 - Photo by <a href="https://unsplash.com/@chilinik?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Nikita Kostrykin</a> on <a href="https://unsplash.com/s/photos/playstation-2?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  
XBOX controller - Photo by <a href="https://unsplash.com/@christaljaard?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Chris Taljaard</a> on <a href="https://unsplash.com/s/photos/xbox?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>

SNES - Photo by <a href="https://unsplash.com/@korie?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Korie Cull</a> on <a href="https://unsplash.com/s/photos/snes?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>

SNES controller main page - Photo by <a href="https://unsplash.com/@derekstory?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Derek Story</a> on <a href="https://unsplash.com/s/photos/retro-gaming?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>

Gamecube - Photo by <a href="https://unsplash.com/@north_of_rapture?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Paweł Durczok</a> on <a href="https://unsplash.com/s/photos/nintendo?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>

Mario home page - <a href="https://pixabay.com/photos/mario-figure-game-nintendo-super-1558068/"></a>

SNES alt image - <a href="https://pixabay.com/photos/video-game-console-video-game-play-2202592/">SNES image</a>

Megadrive alt image - <a href="https://pixabay.com/photos/video-game-console-video-game-play-2202625/">Megadrive image</a>

Playstation alt image - <a href="https://pixabay.com/photos/video-game-console-video-game-play-2202613/">PS1 image</a>

Playstation alt image 2 - <a href="https://www.pexels.com/photo/photo-of-play-station-game-console-and-remote-controller-4219883/">PS1 image 2</a>
Photo by Karolina Grabowska from Pexels

Gamegear alt image - <a href="https://pixabay.com/photos/video-game-console-video-game-play-2202621/">Gamegear image</a>

Saturn alt image - <a href="https://pixabay.com/photos/video-game-console-video-game-play-2202628/">Saturn image</a>

Master System alt image - <a href="https://pixabay.com/photos/video-game-console-video-game-play-2202628/">Master System image</a>

DESCRIPTIONS

SNES - from Wikipedia - <a href="https://en.wikipedia.org/wiki/Super_Nintendo_Entertainment_System"></a>
NES - from Wikipedia - <a href="https://en.wikipedia.org/wiki/Nintendo_Entertainment_System"></a>
N64 - from Wikipedia - <a href="https://en.wikipedia.org/wiki/Nintendo_64"></a>
Mastersystem - from Wikipedia - <a href="https://en.wikipedia.org/wiki/Master_System"></a>
Megadrive - from Wikipedia - <a href="https://en.wikipedia.org/wiki/Sega_Genesis"></a>
Dreamcast - from Wikipedia - <a href="https://en.wikipedia.org/wiki/Dreamcast"></a>
Playstation 1 - from Wikipedia - <a href="https://en.wikipedia.org/wiki/PlayStation_(console)"></a>
Playstation 2 - from Wikipedia - <a href="https://en.wikipedia.org/wiki/PlayStation_2"></a>
Gameboy - from Wikipedia - <a href="https://en.wikipedia.org/wiki/Game_Boy"></a>
Gamegear - from Wikipedia - <a href="https://en.wikipedia.org/wiki/Game_Gear"></a>
Gamecube - from wikipedia - <a href="https://en.wikipedia.org/wiki/GameCube"></a>
SNES controller - from wikipedia - <a href="https://en.wikipedia.org/wiki/Super_Nintendo_Entertainment_System#Peripherals"></a>
NES controller - from wikipedia - <a href="https://en.wikipedia.org/wiki/Nintendo_Entertainment_System#Controllers"></a>
Playstation controller - from wikipedia - <a href="https://en.wikipedia.org/wiki/PlayStation_controller"></a>
X-Box controller - from wikipedia - <a href="https://en.wikipedia.org/wiki/Xbox_controller"></a>
Sega Saturn - from wikipedia - <a href="https://en.wikipedia.org/wiki/Sega_Saturn"></a>


### Acknowledgements
* My Mentor Adegbenga Adeye for assistance and feedback - he's great!

* Tutor support at Code Institute for their support. They have been a massive help at the end of this project when my nerves were in tatters!

* Slack support - this has been really helpful and it is slightly comforting that others have encountered similar issues along the way.


[Back to Table of contents](#table-of-contents)
___

# Screenshots

## Project screenshots

Home page on website <img src="/media/home-page.png" alt="Home page on website."/>

Product page on website <img src="/media/products-page.png" alt="Products page on website."/>

Bag page on website <img src="/media/bag-view.png" alt="Bag page on website."/>

Checkout page on website <img src="/media/checkout-page.png" alt="Checkout page on website."/>

Contact page on website <img src="/media/contact-page.png" alt="Contact page on website."/>
