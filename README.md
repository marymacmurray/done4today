# moonMan

moonMan is a web app for people who feel more at home looking up into the stars than they do lounging in their earthly homes. With moonMan’s new app, use the interactive and intuitive interface to easily browse through a collection of new and used space ship parts that, when all put together, will allow you to travel the expanse of virtual space. Don’t see the parts you need, search, add, edit, and delete many of components you find. Favorite your parts, add them together, and off you go, whether you are trying to find the planet on which you were probably born, or if your’e just visiting. Includes Authentication and authroization features.

Created, designed, and developed by Mary Mac Mac Murry, Ro Cosenza, Jonathan Hernandez, and Rico DeRosa, for the GA Software Engineering Immersive (May '19 Cohort) Unit 3 Project.

## Feature List
Features of moonMan include browsing, searching, wish list, and CRUD operations. 

### MVP

#### Current working features
* User Auth(Sign in/Sign up/Auth view)
* Item display
* Update Item

#### New Features

* User creates a wishlist
* User adds items to wishlist
* User deletes items from wishlist
* User edits items on wishlist
* Homepage shows wishlist

* Interactive 404 page as well as a loading icon/page. 
* Animation effects for certain clicks. 


#### Bug Fixes
* Stay loggedin if page is refreshed.
* fix itemCreate (you have to refresh page/log out and back in to see it)
* fix itemDelete (you have to refresh page/log out and back in to see it)

### Post-MVP:
* React Bootstrap:  Material UI theme
* User can add more Wishlists
* User can change background color/image of wishlist page
* User can move items from one wishlist to another
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

