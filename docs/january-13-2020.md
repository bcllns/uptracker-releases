---
title: January 13, 2020
date: 2000-01-13
slug: january-13-2020

---
### Fixed

* Shopping List: The order "Total" is not displaying for all orders on right side
* Inventory:  Add inventory view: while view is loading a request is made without the user adding any input
* Orders: When reconciling - when you update the cost and click "update for future orders", the cost is not updating in Marketplace
* Marketplace: When in Global Marketplace -  under "Filter" - "department" does not filter
* Inventory: When doing a Stock count - there are  search + scroll issue: items are not uploaded
* Shopping List: When adding shipping and tax, the total price does not adjust
* Marketplace: When a user does a quick edit and hits save, there is a lag and no spinning wheel to show that it is being processed. User May hit save over and over cause they don’t realize it is working
* Inventory:  if you enter a Keyword in the Search section, the Keyword doesn't clear when Reset is clicked.
* Inventory: If you search for a product that contains a "-", and probably any special character, the input goes crazy and adds ///////

### Updated

* General: Button spinner  when the program is saving or loading was changed to a better looking spinner
* Shopping List: When a user is ordering for multiple locations on one PO the “ship to” box should be red to make user aware they have to select one
* Marketplace:  After adding a custom product with a custom vendor, if the user clicks to Work On Your Custom vendor, it should go to the vendor detail view, not to the all vendors view
* Shopping List: When a user goes to change a price the default for “all future orders” should be selected instead of “one time” - also make the “save button” a button
* Marketplace: On the final step of a custom product creation, make the view as tall possible so viewer can see more products on a screen
* Orders: Change date on orders section to be 01/01/20 instead of 01/01/2020 so that the year is not cut off -- instead of truncating the date let's fix the column spacing so any date column is never shrunk
* Orders: When you do a Bulk edit: disable the button and add spinner instead on click

### New

* Inventory: On the tile if the item is a Global Product, always show the "globe" icon.  If the item contains a variant that is in an inv group, also add a "box" icon.
* Inventory: When a new group is being added, have the program check if the product exists in another inv. groups
* Locations: Prevent deletion of the location if there is only one left