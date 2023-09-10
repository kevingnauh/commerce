# Purpose
To explore and learn the Django framework. This project utilizes Python, HTML, and CSS.

# Description
An eBay-like e-commerce auction site that allow users to post auction listings, place bids on listings, comment on those listings, and add listings to a watchlist.

# Features
### Create Listing
  - Users can create a new listing by specifying a title for the listing, a text-based description, and what the starting bid should be.
  - Users can also optionally provide a URL for an image for the listing and/or a category.
### Active Listings Page
  - The default route of the web application lets users view all of the currently active auction listings.
### Listing Page
  - Clicking on a listing will take users to a page specific to that listing. On that page, users can view all details about the listing, including the current price for the listing.
  - If the user is signed in, the user can add the item to their Watchlist. If the item is already on the watchlist, the user can remove it.
  - If the user is signed in, the user can bid on the item. The bid must be at least as large as the starting bid, and must be greater than any other bids that have been placed (if any). If the bid doesn't meet those criteria, the user will be presented with an error message.
  - If the user is signed in and is the one who created the listing, the user can "close" the auction from this page, which makes the highest bidder the winner of the auction and makes the listing no longer active.
### Watchlist
  - Users who are signed in can visit a Watchlist page, which will display all of the listings that a user has added to their watchlist. Clicking on any of those listings will take the user to that listing's page.
### Categories
  - Users can visit a page that displays a list of all listing categories. Clicking on the name of any category will take the user to a page that displays all of the active listings in that category.
