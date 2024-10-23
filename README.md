The goal of my app, Warehouse Friend, was to use a room-code system for managing warehouse inventory and users. This meant interfacing with two database tables, one for items and another for users, 
and being able to work with that data through shared room code ID values between both databases. I included functionality to edit items, edit users, create items, create users, view all items, and 
view all users. The main screen I had was a screen that listed all items. An authorized user could hit a button to switch the list to all users. It's a small thing but being able to change view 
modes on the same screen gave it a nice flow. I kept all the UI elements nice and visible and scalable thanks to the way modern Android UI works. I would consider my interface successful because
it follows the system theme, exposes large amounts of data, is unobtrusive but still present, and still provides a good surface area for its elements. I approached the process of coding my app
by forming my battle plan for data structures and their interfaces and building off of those, data structures first, meaning the first thing I implemented were the user and item objects, then
their databases, then their interfaces. I also used alot of Log.d() commands to troubleshoot and implemented many redundancies to avoid crashes. Something I had to do was implement a dummy object system
for each database, meaning an item 0 existed in each database until an item 1 was created, after which item 0 would be removed. For testing, I used many Log.d commands as well as frequently testing
in the emulator. It was important to know where my code was getting hung up and why, and to see that every little function I had worked. I think that my database management was the best display
of my accrued knowledge. I made my database system pretty feature rich and I was proud of how my user and item management worked. 

I went back and fixed my app too!
