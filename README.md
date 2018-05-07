# GifTastic

**Overview**

90s Cartoon Gifs was created for the Giftastic homework assignment for Berkeley Coding Bootcamp using the GIPHY API to make a dynamic web page that populates with gifs of our choice by calling the GIPHY API and using JavaScript and jQuery to change the HTML of our site.

**Requirements**

- Create an array of strings, each one related to a topic that interests us. Save it to a variable called `topics`.
    * I chose the 90s Cartoon theme.
- App should take the topics in our array and create buttons in our HTML using a loop that appends a button for each string in the array.
- When the user clicks on a button, the page should grab 10 static, non-animated gif images from the GIPHY API and place them on the page.
- When the user clicks on one of the still GIPHY images, the gif should animate. If the user clicks the gift again, it shoudl stop playing.
- Under every gif, display its rating (PG, G, so on).
    * This day is provided by the GIPHY API.
- Add a form to the page that takes a value from a user input box and adds it into your `topics` array. Then make a function call that takes each topic in the array remakes the button on the page.

**Bonus Goals**

1. Ensure your app is fully mobile responsive.
2. Allow users to request additional gifs to be added to the page.
    *Each request should ADD 10 gifs to the page, NOT overwrite the existing gifs.