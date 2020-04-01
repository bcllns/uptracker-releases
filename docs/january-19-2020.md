---
title: January 19, 2020
date: 2020-01-19
slug: january-19-2020

---
### Fixed 

* Marketplace: "Keyword search" text doesn't fit the field in Marketplace tab
* Vendor: The "Edit vendor" button is overlapped by "chat" button
* Inventory: User can't select all items in Inventory when in the grid view
* Shopping List: When sending an order by E-mail, all of the shipping info fields are empty.
* Inventory: When scrolling to load all of the Tiles in inventory,  after being reloaded several times in a row the first ten items are not displaying
* Inventory:  When you filter on "Vendor", the filter works incorrectly, not all products are showing
* Orders: When you do an"Edit" for "Location", it does not update the Location on the order
* Orders: When reconciling, there is an issue when you do a Reconcile Split  
* Inventory: When doing a Stock Count - a user can enter a negative number in "Actual QTY" field 
* Inventory: Client gets an error when they try to order the item from an inventory group
* Inventory:  When you select a location, the inventory quantity doesn't update immediately
* Shopping List:  When you Print a PO, the "Total" value is 0.00 
* Marketplace: When you try to create an inventory group from Marketplace, you get an error
* Shopping List:  When clicking on Checkout with a Location selected the preview does not display
* Shopping List: When a client checks "Select all" and then un-checks any product, the "Select All" is staying activated.
* Shopping List: Sending an email. The "Send" button is grayed out. You need to click on the To/From addresses to turn it blue

### Updated

* Inventory: Update view so when you click on the "Grid" icon, all the inventory groups will be listed. We need to add the ability for the user to add items directly to their shopping cart from here.
* Shopping List: Remove Shipping Method required from checkout
* Shopping List: Disable changing location in the Shopping list when the user has only one location
* General: Better Error Messaging: we need to display more detailed error messages for the user if it is an issue with an action they have taken, for example a CC declined 

### New

Reports:  The development of Order History report has been started. The layout of the report has been finalized and the "Sort By" options have been tested.