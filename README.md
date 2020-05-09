# Front End Milestone Project - *Restaurant Website*

This milestone project demonstrates my ability to create a "mobile first" website using **HTML5, CCS and CDNs**.

Website Link : https://kelvinhere.github.io/Milestone-FrontEnd/

This restaurant is aimed at workers looking for quick healthy food and will be designed to give this impression via color palet and background images through the site.

This restaurant websites aim is to attract customers and boost sales.  The main page quickly gives users an idea of the style of food available and ethos of the company.  This website also includes an **online 
menu** with prices and expandable nutrition/allergen information and **QR code** for quick automatic ordering.  A **location page** with map link and opening hours. A customer **Event** page will encourage repeat custom via weekly events, discounts and free workplace lunch deliveries won by draw.

## UX

This website is for health conscious workers looking to buy good quality, healthy fast food.  
Primarily the users will want to view the different menu items quickly to make a dining choice.  The best way to achieve this is a quick modern 
looking interface to access these choices with as few clicks as possible, from the main page the rest of the menu and location information are accessible by one click.

#### User stories
* As Bob a previous customer, I want to choose something to eat because I'm hungry.
* As Charlie, a friend recommended the restaurant, I want to find out where it is so I can visit.
* As Sue, an allergy sufferer, I want to view the allergens in the food so I don’t have a bad reaction.
* As Bill, a serial customer, I want to know this week's event, and I want to try to win the office delivery draw.
* As Pat, a health conscious person, I want to know the ingredients of my lunch, so I can stay within my nutrition boundaries.
* As Frank, a shift worker, I want to know the opening hours, so I am not wasting a trip to the restaurant. 
* As Paulie, I want to order without talking to anyone, I want to use the QR code self service option.

#### wireframes
##### Mobile wireframes
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

##### Main page
* A hero image to display the kind of foods available and set the tone of the company ethos.  This will have the restaurant name, hero image, 
and links to all other pages on the site.

##### Food Menu Page
* Shows off the restaurants dishes.
* Menu items are clickable, opening up a larger image in a bootstrap modal, this gives more information on nutrition and allergens.  
* From the menu item model there will be a QR order button that will expose a QR code to self service order in the restaurant.

##### Events page
* A page to show current events and enter a weekly delivery draw.  This page's goal is to give the customers a reason to regularly access the website.
* This page will have an entry form for the draw that will take these inputs from the user :-
    * Name
    * Email
    * Entry Code (5 digit code on receipt)

##### Location page
* A simple page with opening hours, address and an embedded google maps link and GPS coordinates.
 
### Existing Features
- Background image positions changes depending screen width.
- Responsive design will rearrange buttons / columns / tables to appropriate sizes depending on resolution of screen.
- Navigation will collapse to menu icon on mobile to avoid screen being too busy, in this case social media icons will be displayed as footer.
- Social media icons move to top navigation bar at higher resolutions.
- Width of desktop elements are capped to avoid ugly layout and stretched items at very high resolutions.
- Hidden QR codes that only take up screen real estate if needed by the user.
- Footer on main page will hide before it clashes with navigation buttons.
- Background images available in different resolutions depending screen size starting with lower resolutions for mobile, to reduce used bandwidth and speed up site load times over mobile.
- Menu items are clickable and give modal with more in depth information about item.
- Events page enter draw form is available as a modal through a button on mobile or displayed immediately on larger screens.
- Footer images of food items are also a link to the menu page.
- simple javascript button to show hide image
- fontawesome icons
- bootstrap


### Features Left to Implement
- None

## Technologies Used

- [HTML5/CSS3] - Languages
	- **HTML5/CSS3** was used as it is a good industry standard
- [Gitpod](https://www.gitpod.com) - IDE
	- **Gitpod** was used for its one stop contained development workflow via browser
- [Github](https://www.gitpod.com) - Version Control
	- **Github** was used for its robust repository and ability to view website through Github pages
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
- Each website page has been checked with the HTML validator at validator.w3.org, errors and warnings have been corrected.

### Visual inspection
* Through Chrome browser inspect function, responsive layout, features and links tested on :-
    * Desktop - Variable resolutions from 2560 x 1440 to 800 x 600 - Also tested on Firefox/Edge/Opera
    * Moto G4
    * Galaxy S5
    * Pixel 2/2XL
    * iPhone 5/SE/6/7/8
    * iPhone 6/7/8 plus
    * iPhone X
    * iPad / iPad Pro

- The above tests made sure that

    * All pages have
        * The navbar is collapsed on small screen and uncolapses at lager resolutions
        * Uncolapsed navbar has social media links
        * Active page is marked on navbar
        * The top right branding links to index.html
        * Background image is chosen  and positioned depending on screen size
        * If table exists at bottom of page it scales with width and changes from 1 column to 3 columns on wider screens        
        * Footer of social media buttons if navbar is collapsed

    * index.html -
        * The buttons stack horizontally on mobile and spread out vertically on wider screens
        * The logo more appropriatley offsets its self on wider screens to line up with new button layout
        * The hero image takes up most of the screen vertically but leaves enough to show user can scroll down to next section at any screen height resolution
        * The catchphrase hides when screen becomes to small to avoid clutter
        * Footer social media links hide when vertical height is too small and collides with buttons

    * menu.html -
        * Menu items image and description stack horizontally on mobile and vertically on larger screens
        * On higher resolutions the maximum width of the page content is capped for readability
        * Each menu item opens menu modal when clicked
        * Each menu modal has button to toggle QR code visibility and close midal button

    * events.html -
        * Mobile shows events and the ability to enter draw through a button that opens a modal
        * On higher resolutions the maximum width of the page content is capped for readability
        * Wider screens show two columns one for events and one with an enter draw form (the mobile enter draw information is hidden)  
        * Enter draw modal has close and submit button

    * location.html -
        * Location is two vertical stacked items on mobile that turns to two horizontal columns on wider screens
        * On higher resolutions the maximum width of the page content is capped for readability
        * On smaller screens a button is visible that takes you to the opening hours section of the page
        * Location has embeded google maps that centers on restaraunt (used code institue address) and is size reactive
        * Clickable telephone link





        



### Manual Testing
- Each button and link on each page has been tested to link to its correct destination
- The top right "FreshGreen" navigation image acts link back home on each page
- The opacity layers allow the user to see the background without it obscuring text on each page

### User stories tested
- As Bob a previous customer, I want to choose something to eat because I'm hungry.
    * Menu accessible by one click on either mobile or desktop.
- As Charlie, a friend recommended the restaurant, I want to find out where it is so I can visit.
    * Location accessable by one click, google maps embedded link direct to location, underneath are GPS co-ordinates and written address.
- As Sue, an allergy sufferer, I want to view the allergens in the food so I don’t have a bad reaction.
    * Each menu item when clicked shows 'allergen symbols' used by [Erudus](https://erudus.com/)', also under ingredients the allergens are written so customer can double check if unsure of symbol.
- As Bill, a serial customer, I want to know this week's event, and I want to try to win the office delivery draw.
    * One click to events page first item is this weeks event, promonent enter draw button on mobile or entry form on desktop.
- As Pat, a health conscious person, I want to know the ingredients of my lunch, so I can stay within my nutrition boundaries.
    * Each menu item when clicked shows exact ingredients.
- As Frank, a shift worker, I want to know the opening hours, so I am not wasting a trip to the restaurant. 
    * As standard opening hours are included on location page and are accessable in one click.
- As Paulie, I want to order without talking to anyone, I want to use the QR code self service option.
    * QR code available via promonent button once menu item is selected.

## Credits

Created by KelvinHere

### Content
- TODO ################ 

### Media

- Edwin - digital photographer
- Food allergen icons - [Erudus Food Allergy Icons](https://erudus.com/erudus-food-allergy-icons/)
- Crossed grain symbol - [Coeliac Society of Ireland](https://www.coeliac.ie/crossed-grain-symbol/)
- Vegetarian symbol - [European Vegetarian Union](https://www.euroveg.eu/)
- Cafe / doughnut images (Free for commercial use - No attribution required) [Pixabay](https://pixabay.com/)

### Acknowledgements

- My brother Edwin for his photography skills.
- Code Institute.
- My noise canceling headphones, so I can still work during quarantine.


