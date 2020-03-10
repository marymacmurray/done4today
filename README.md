# moonMan

moonMan is a web app for people who feel more at home looking up into the stars than they do lounging in their earthly homes. With moonMan’s new app, use the interactive and intuitive interface to easily browse through a collection of new and used space ship parts that, when all put together, will allow you to travel the expanse of virtual space. Don’t see the parts you need, search, add, edit, and delete many of components you find. Favorite your parts, add them together, and off you go, whether you are trying to find the planet on which you were probably born, or if your’e just visiting. Includes Authentication and authroization features.

## Feature List
Features of moonMan include browsing, searching, wish list, and CRUD operations. 

## Done4Today is a web app for people who feel more at home looking up into the stars than they do lounging in their Earthly homes. 
With moonMan’s new app, use the interactive and intuitive interface to easily browse through a collection of new and used space ship parts that, when all put together, will allow you to travel the expanse of virtual space. 
#### Don’t see the parts you need? 
* Search, add, edit, and delete many of components you find. 
* Favorite your parts, add them together, and off you go, whether you are trying to find the planet on which you were probably born, or if you're just visiting. 
* Includes authentication and authorization features.

## Created, designed, and developed by:
* Mary Mac Mac Murray, 
* Ro Cosenza, 
* Jonathan Hernandez, 
* & Rico DeRosa
for the GA Software Engineering Immersive Mandalorians Unit 3 Project.

## Wireframes
![Mobile Home] Format: ![Mobile Home mockup](https://i.imgur.com/J7V53qA.jpg)
![Mobile Wishlist] Format: ![Mobile Wishlist mockup](https://i.imgur.com/WZPhvv6.jpg)
![Desktop Home] Format: ![Desktop Home mockup](https://i.imgur.com/YGjNMxO.jpg)
![Desktop Wishlist] Format: ![Desktop Wishlist mockup](https://i.imgur.com/kr6VQIW.jpg)


## Feature List
Features of moonMan include:

* Browsing space items
* Searching space items
* Adding space items to wishlist
* CRUD operations

### MVP

#### Bug Fixes
* Stay loggedin if page is refreshed.
* fix itemCreate (you have to refresh page/log out and back in to see it)
* fix itemDelete (you have to refresh page/log out and back in to see it)
*  Updating design to be mobile-centric (responsive)

#### Current working features
* User Auth(Sign in/Sign up/Auth view)
* Item display
* Update Item

#### New Features
* User Auth(Login/Register)
  * Stay logged in if page is refreshed
* Wishlist functionality-
  * User creates a wishlist
  * User adds items to wishlist
  * User deletes items from wishlist
  * User edits items on wishlist  
  *  Homepage shows wishlist 
* Search functionality
  * Includes a search bar


### Post-MVP:
* React-Bootstrap Material UI 
  *  Animation effects for certain clicks
  *  Interacting 404 page as well as a loading icon/page

* Screen for Meteor and Asteroid alerts (asteroid alert api required). 
* Facts section of UFO sightings with suggested items to purchase to prepare. 
* Marketplace to hire fellow space-goers and friendly aliens as travel companions/navigators/general crew members.
* Add images to each item
* Sound effects

### Component Hierarchy:

```
Container
  |__ Wishlist
  |__ Search
     |__ ItemsDisplay

```


### Dependencies:
MongoDB, Mongoose, Express, Axios, cors, bcrypt, Body-Parser, Morgan, Faker, Jest, Supertest, NodeJS, React/React Router
