#Ionic item bug

Scroll to bottom of list on iphone capacitor/iphone safari and see first click is ignored and list view is moving (see gif).

To reproduce this:
1. Ion content with some padding (50px here) and scrollEvents true
2. --background-activated-opacity: 1 and "button" on item
3. Scroll to very bottom of list and click on an item
4. See list i "moving" and click is ignored, second click will work
