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
* As Bill, a serial customer, I want to know this week's event, so I can try to win the office delivery draw.
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
- [Draw.io](https://www.draw.io/) - Wireframing tool
	- This project uses **Draw.io** for rapid wireframe prototyping

## Testing

### HTML Validator
- Each website page has been checked with the HTML validator at validator.w3.org, errors and warnings have been corrected (NOT FINALISED) 

### Visual inspection
* Through chrome browser inspect, layout and features tested on :-
    * Desktop - Variable resolutions from 2560 x 1440 to 1920 x 720 - Chrome/Firefox/Edge/Opera
    * Moto G4
    * Galaxy S5
    * Pixel 2/2XL
    * iPhone 5/SE/6/7/8
    * iPhone 6/7/8 plus
    * iPhone X
    * iPad / iPad Pro

## Credits

Created by KelvinHere

### Content
- TODO ################ 

### Media

- Edwin - digital photographer
- Food allergen icons - [Erudus Food Allergy Icons](https://erudus.com/erudus-food-allergy-icons/)
- Crossed grain symbol - [Coeliac Society of Ireland](https://www.coeliac.ie/crossed-grain-symbol/)
- Vegetarian symbol - [European Vegetarian Union](https://www.euroveg.eu/)
- Free online QR code generator - [QR Code Monkey](https://www.qrcode-monkey.com/)
- Cafe / doughnut images (Free for commercial use - No attribution required) [Pixabay](https://pixabay.com/)

### Acknowledgements

- My brother Edwin for his photography skills.
- Code Institute.
- My noise canceling headphones, so I can still work during quarantine.


