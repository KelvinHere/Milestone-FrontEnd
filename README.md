# <p style="text-align: center;">**FreshGreen - Restaurant**</p>
[FreshGreen Website link](https://kelvinhere.github.io/Milestone-FrontEnd/ 'FreshGreen website GitHub pages link')
 
A stylish reactive mobile first website for FreshGreen restaurant to attract customers and increase repeat custom.  FreshGreen caters to workers for eat in and take-away
healthy food, and is designed to give this impression via color palette and background images throughout the site.
 
The FreshGreen website will allow a customer to quickly find all critical information in as few clicks as possible while keeping a slick uncluttered look.  While browsing the 
customer will be funneled to one of the restaurants USPs, a **QR quick order code**, allowing fast purchase from one of the restaurant's take-away kiosks.
 
Business goals
* Promote brand awareness
* Drive custom and repeat custom to the restaurant
* Promote use of self service to reduce need for front of house staff during peak periods
* Increase sales from customers with allergens by including allergy information
 
Customer goals
* Easy to use UX for accessibility to all needed information
* Easy to read menu items that give customer more information when clicked
* Quick ordering process
* Give customers who suffer from allergies quick access to menu item allergens
* Quick access to location and opening hours
* One click navigation to important information
 
## UX
 
Visitors to this site will be choosing something to eat or finding out more information about the restaurant.  All design is built keeping these core tasks in mind.
 
This website is customer based, and will be viewed mostly on mobile devices. To achieve best results the UX needs to be simple and allow the user to reach their information through as few clicks as possible.  Because of
screen size limitations of mobile devices the UI will be mostly vertically stacked, but for our desktop users the website will reorder into a wider column based design.  Both designs allow the user to view its content without cluttering the screen.
 
### User stories
* As a previous customer, I want to choose something to eat because I'm hungry.
* As Charlie, a friend recommended the restaurant, I want to find out where it is so I can visit.
* As an allergy sufferer, I want to view the allergen information so I don’t have a bad reaction.
* As a serial customer, I want to know this week's event because it adds value to my visit
* As Bob, I want to try to win the office delivery draw because I want to win lunch for my workmates.
* As a health conscious person, I want to know the ingredients of my lunch, so I can stay within my nutrition boundaries.
* As Paulie, I want to order without talking to anyone, I want this service option.
* As a shift worker, I want to know the opening hours, so I am not wasting a trip to a closed restaurant. 
 
 
### Wireframes
#### Mobile wireframes
![Mobile1](https://github.com/KelvinHere/Milestone-FrontEnd/blob/master/design-assets/mobile1.jpg?raw=true "Mobile mockup index and menu")
![Mobile2](https://github.com/KelvinHere/Milestone-FrontEnd/blob/master/design-assets/mobile2.jpg?raw=true "Mobile mockup events and location")
##### Index page on desktop
![Index Mockup](https://github.com/KelvinHere/Milestone-FrontEnd/blob/master/design-assets/index-desktop.jpg?raw=true "Index page mockup on desktop")
#### Menu page on desktop
![Menu Mockup](https://github.com/KelvinHere/Milestone-FrontEnd/blob/master/design-assets/menu-desktop.jpg?raw=true "Menu page mockup on desktop")
#### Menu modal select on desktop
![Menu Modal Mockup](https://github.com/KelvinHere/Milestone-FrontEnd/blob/master/design-assets/menu-modal-desktop.jpg?raw=true "Menu modal page mockup on desktop")
#### Events on desktop
![Events Mockup](https://github.com/KelvinHere/Milestone-FrontEnd/blob/master/design-assets/events-desktop.jpg?raw=true "events page mockup on desktop")
#### Location on desktop
![Location Mockup](https://github.com/KelvinHere/Milestone-FrontEnd/blob/master/design-assets/location-desktop.jpg?raw=true "location page mockup on desktop")
 
 
## Features
 
### Existing Features
 
##### Main page
The front page of the website is as simple as possible while giving the user the ability to get to any page in one click, the page only gets "busy" as you scroll down and want to see more images of the restaurant / food for sale.
* A hero image to set the tone of the company ethos and expected type of product.  This will have links to all other pages on the site through main page buttons and navbar.
* Footer on the index page will hide before it clashes with navigation buttons (for lower resolution screens).
* A reactive set of images of the restaurant and pictures of some food available will be at the bottom of the page, if clicked links to [Menu Page](https://kelvinhere.github.io/Milestone-FrontEnd/menu.html "Menu page for FreshGreen")
 
##### Menu Item Page
This page is made to allow the customer to quickly scan through menu items and get an idea of what they may want, extra information is only shown if the user clicks an item to avoid information overload.
* Shows off the restaurant's menu items through a picture and simple descriptive text
* Menu items are clickable, opening up a larger image in a bootstrap modal, this gives more information on nutrition and allergens.  
* From the menu item model there is a QR order button that exposes a QR code to self service order in the restaurant.
 
 
##### Events page
The events page is to encourage repeat custom, having a page updated weekly gives users a reason to revisit the site even if they already know the menu.
* A page to show current events and enter a weekly delivery draw.  This page's goal is to give the customers a reason to regularly access the website.
* Events page **enter draw** form is available as a modal accessed through a button on mobile or displayed immediately in a column on larger screens.
* The **draw** form takes the below inputs from the user, correct formats needed for email and entry code :-
    * Name
    * Email
    * Entry Code (5 digit code on receipt)
* A reactive set of images of the restaurant and pictures of some food available will be at the bottom of the page, if clicked links to [Menu Page](https://kelvinhere.github.io/Milestone-FrontEnd/menu.html "Menu page for FreshGreen")
 
##### Location page
The location page simply gives customers the ability to locate / contact and find opening hours of the restaurant.
* A simple page with opening hours, clickable phone number, address and an embedded google maps link and GPS coordinates.
* If viewing the map on smaller screens the opening hours are not usually visible, in this case a prominent **Opening Hours** button will appear on screen with a direct link to them to avoid the user missing this information.
* On larger screens the **Opening Hours** button is not needed so will be hidden.
* A reactive set of images of the restaurant and pictures of some food available will be at the bottom of the page, if clicked links to [Menu Page](https://kelvinhere.github.io/Milestone-FrontEnd/menu.html "Menu page for FreshGreen")
 
##### Global features
* Some background image positions/magnifications change depending on screen width.
* Background images are available in different resolutions depending on screen resolution starting with lower resolutions for mobile, to reduce used bandwidth and speed up site load times over mobile.
* Responsive design will rearrange buttons / images / columns / tables to appropriate sizes depending on resolution of screen **as shown in wireframes**.
* Navigation will collapse to a menu icon on mobile to avoid the screen being too busy, in this case social media icons will be displayed as a Footer.
* Social media icons move to the top navigation bar at higher resolutions.
* Width of some elements are capped to avoid ugly layout and stretched items at very high resolutions.
* simple javascript button to show hide image.
* FontAwesome icons.
* Google fonts.
* bootstrap.
 
### Features Left to Implement
* None
 
### Features removed/changed during development
* Removed : Allergen information placed on to picture of food item
    - Reason : Image looked messy or icons were too small and unreadable so were removed but can still be seen when item is clicked
* Changed : Index page buttons stack underneath hero image on small screens
    - Reason : Buttons could be off page, placing them on hero image created a better looking UI
* Changed : Menu page items have text next to image on mobile
    - Reason : Text was too small, text moved below menu item
* Changed : Menu page items are on a double column on larger screens
    - Reason : Information overload, replaced with single column of items
 
### Future features
* GDPR compliance
* Language select
* Add drinks option to QR checkout code
 
## Technologies Used
 
- **HTML5/CSS3** - Languages
    - **HTML5/CSS3** industry standard web development
- [Gitpod](https://www.gitpod.com) - IDE
    - **Gitpod** was used for its one stop contained development workflow via browser
- [Git](https://git-scm.com/) - Version-control system
    - **Git** Used to version control the project
- [Github](https://www.gitpod.com) - Code hosting platform
    - **Github** was used for its robust repository system and ability to view website through **GitHub Pages**
- [Bootstrap](https://getbootstrap.com) - Library
    - This project uses **Bootstrap** for rapid development
- [Fontawesome](https://fontawesome.com) - Font library
    - This project uses **Fontawesome** for quick icon styling
- [Google Fonts](https://fonts.google.com/) - Font library
    - Used to style websites fonts
- [Draw.io](https://www.draw.io/) - Wireframing tool
    - This project uses **Draw.io** for rapid wireframe prototyping
- [QR Code Monkey](https://www.qrcode-monkey.com/) - Free online QR code generator
    - Used to create QR codes for menu items
- [Photoshop CS1](https://www.adobe.com/) - Image editing software
    - Used to edit images on the website
- [Inkscape](https://inkscape.org/) - Vector graphics software
    - Used to create logo for website
 
## Testing
 
### HTML Validator
- Each page has been checked with the HTML validator at validator.w3.org, errors and warnings have been corrected.
- Each page has been spell checked with [W3C Spell checker](https://www.w3.org/2002/01/spellchecker 'W3C spell checker link').
 
### Visual inspection and manual testing
* Visually inspected through the Chrome browser inspect function to confirm the responsive layout, features and links work as intended on all the below platforms :-
    * Desktop - Variable resolutions from 2560 x 1440 to 800 x 600 - Also tested on Firefox/Edge/Opera
    * Moto G4
    * Galaxy S5
    * Pixel 2/2XL
    * iPhone 5/SE/6/7/8
    * iPhone 6/7/8 plus
    * iPhone X
    * iPad / iPad Pro
 
* All pages have had the below items tested :-
    * The navbar is collapsed on small screen and un-collapses at lager resolutions
    * Un-collapsed navbar has social media links
    * Active page is highlighted on navbar
    * The top right branding links to index.html
    * The opacity layers allow the user to see the background without it obscuring text on each page
    * Each button and link on each page has been tested to link to its correct destination
    * Background image is chosen and positioned depending on screen size
    * If a table exists at bottom of page it scales with width and changes from 1 column to 3 columns on wider screens        
    * Social media buttons appear as a footer if the navbar is collapsed
    * The reactive elements of the website look good when adjusting the width/height of the website to any sensible resolution
 
* index.html -
    * The buttons stack horizontally on mobile and spread out vertically on wider screens
    * The logo more appropriately offsets its self on wider screens to line up with new button layout
    * The hero image takes up most of the screen vertically on any screen but leaves enough to show the user there is more content below
    * The catchphrase hides when screen becomes tot small to avoid clutter
    * The footer social media links hide when vertical height is too small and would collide navigation with buttons
 
* menu.html -
    * The food items **image** and **description** stack horizontally on mobile and vertically on larger screens
    * At higher resolutions the maximum width of the page content is capped for readability
    * Each menu item opens menu modal when clicked
    * Each menu modal has button to toggle QR code visibility and close modal button
 
* events.html -
    * Mobile screens shows current **event** in full and the ability to enter the draw through a prominent button that opens a modal
    * Higher resolution screens show two columns one for events and the other a form to enter the draw (the mobile screen enter draw button and associated text is hidden)  
    * On higher resolution screens the maximum width of the page content is capped for readability
    * Enter draw modal has close and submit button
    * The Enter draw form only accepts valid inputs.
        * Name - accepts any text
        * Email - gives an error when incorrect email format is entered
        * Entry - code gives an error unless it is a 5 digit code
 
* location.html -
    * Location page is two vertically stacked items on mobile that turns to two horizontal columns on wider screens
    * At higher resolutions the maximum width of the page content is capped for readability
    * On smaller screens a button is visible that takes you to the opening hours section of the page
    * Location has embedded google maps that centers on restaurant (used Code Institute address) and is size reactive
    * Clickable telephone link
  
### User stories tested
- As a previous customer, I want to choose something to eat because I'm hungry.
    * Menu accessible by one click on either mobile or desktop.
- As Charlie, a friend recommended the restaurant, I want to find out where it is so I can visit.
    * Location accessible by one click, google maps embedded link to location, underneath are GPS coordinates and written address.
- As an allergy sufferer, I want to view the allergen information so I don’t have a bad reaction.
    * Each menu item when clicked shows 'allergen symbols' used by [Erudus](https://erudus.com/)', also under ingredients the allergens are written so customers can double check if unsure of the symbol.
- As a serial customer, I want to know this week's event because it adds value to my visit
    * One click to events page, the first item is this week's event, prominent **Enter draw** button on mobile or entry form on desktop.
- As Bob, I want to try to win the office delivery draw because I want to win lunch for my workmates.
    * The events page allows bob to enter the draw with a valid receipt code
- As a health conscious person, I want to know the ingredients of my lunch, so I can stay within my nutrition boundaries.
    * Each menu item when clicked shows exact ingredients.
- As Paulie, I want to order without talking to anyone, I want this service option.
    * QR code available via a prominent button once the menu item is selected.    
- As a shift worker, I want to know the opening hours, so I am not wasting a trip to a closed restaurant. 
    * As standard, opening hours are included on the location page and are accessible in one click.
 
## Deployment
 
### Deployment Location
Website created and developed in GitPod, version controlled with Git and hosted on GitHub
 
The template used to start this project was from [Code Institute](https://codeinstitute.net/ 'Code Institute link') and was the [Code Institute - GitPod Full Template](https://github.com/Code-Institute-Org/gitpod-full-template 'Code Institue GitPod template')
This template sets up some config files, installs tools such as Heroku, MongoDB, MySql and python extensions to GitPod.
 
To use this template on GitHub
* Log into GitHub.
* Visit [Code Institute - GitPod Full Template](https://github.com/Code-Institute-Org/gitpod-full-template 'Code Institue GitPod template') and select the green **Use this template** button.
* On the next page give this new repository a name, description and press the green **Create repository from template** button.
 
#### Using git
During development the project was version controlled using Git. [Commit History](https://github.com/KelvinHere/Milestone-FrontEnd/commits/master 'GitHub commit history for FreshGreen')
 
Process
* Locally from GitPod files were added by `git add .` or `git add (filename)`
* Files were then committed to the local master branch with `git commit -m "Appropriate message describing commit"`
* The local master branch was then pushed to the remote master branch located on **GitHub** the code hosting platform, through the command `git push`
* Being the only contributor to this project I did not have to contend with any merges
* If a feature did not work out the project was rolled back to a previous commit (labeled by an appropriate commit message) process below
    - Find the commit you want to restore on your remote master branch and get the first 6 commit numbers
    - run this command `git reset --hard #the first 6 commit numbers here`
    - The project will be restored to this commit point
 
#### Live site location
This webpage has been deployed to github pages - [FreshGreen Link](https://kelvinhere.github.io/Milestone-FrontEnd/ 'FreshGreen link hosted on GitHub pages')
 
Steps to publish to GitHub Pages
1. From [this repos main page](https://github.com/KelvinHere/Milestone-FrontEnd 'Reop main page link') click **settings** (cog icon)
2. Under the 'GitHub Pages' > 'Source' section click the **None** button
3. From dropdown menu select the **master branch** to publish the master branch on GitHub pages
4. Once published the link to the live page will be shown in the **GitHub Pages** section
 
### Deploy locally
 
To clone FreshGreen website from GitHub :-
1. In your IDE terminal, navigate locally to the directory you want the repository to be stored.
2. Run the command `git clone https://github.com/KelvinHere/Milestone-FrontEnd.git`
3. Project will now be cloned to your locally selected directory.

## Credits
 
- Created by KelvinHere
 
### Content
 
- Text on this website created by KelvinHere
 
### Media
 
- Digital photography of food and backgrounds - Edwin, digital photographer
- Food allergen icons - [Erudus Food Allergy Icons](https://erudus.com/erudus-food-allergy-icons/)
- Crossed grain symbol - [Coeliac Society of Ireland](https://www.coeliac.ie/crossed-grain-symbol/)
- Vegetarian symbol - [European Vegetarian Union](https://www.euroveg.eu/)
- Cafe / doughnut images (Free for commercial use - No attribution required) [Pixabay](https://pixabay.com/)
 
### Acknowledgements
 
- My brother Edwin for his photography skills.
- Code Institute.
- My mentor Spencer.
- My noise canceling headphones, so I can still work during quarantine.