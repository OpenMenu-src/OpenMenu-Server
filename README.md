# OpenMenu-Service
*An open-source system for restaurant menus.*

This is the backend server for the OpenMenu Service. This will house the WebUI and the API server for clients and an eventual app.

I'll fill this out with a lot more detail once this becomes a more filled repo. 

I chose rails for this as it's what I've really been enjoying recently.

## How does it work?
This is the server side, where a user will interact with the system. 

A user will make their profile and then create a business within said profile. Businesses can then create menu items and menus. Each business will be allowed a set number of items, and you can have a set number of menus. 

When a user has made their menus, they can then choose a number of ways to present said menu. I plan on supporting a wide variety of feed-types, including JSON via a REST API and an RSS Feed to start.

I plan on making something along the lines of a Pi image for users to be able to display the menu from the API on a TV. This will be a future repository once the server is created, though. A basic rundown of how that will work would be to use a call to the server every 30 secs. or so, pulling the JSON data, formatting it, and then displaying it. Another easy way would be to use a simple web-view and just AJAX display the content, which is how I plan on allowing a customer to view the menu on a mobile device. 

## Will this software stay FOSS?
Yes! I plan on keeping this FOSS for as long as I can. I plan on hosting a version of this myself, but of course anyone can host it on their own. 