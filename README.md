# hw-w02d05: Duck Hunt / Game of Zones
![](https://media.giphy.com/media/k7UpjV0TawvlK/giphy.gif)

## Requirements:
Part 1 is required, Part 2 is optional!  Part 2 is an EXCELLENT challenge.  You don't have to do it but if you do you'll be very prepared for projects next week :).

## Part 1:  Duck hunt:

Your homework tonight is to finish the duckhunt lab!  Please copy/paste this into the work you did in class and answer the questions in your javascript file:
```javascript
  // 5. ——— Part 2: Here we go! —— 
  // 6. Things are getting a bit messy. Put everything from problems 1-4 in a new function 
  // called createDuck that "returns" the duck object

  // 7. Now, let's create lots of ducks!  Use a "for" loop to create 5 ducks
  //    using our fancy new createDuck() function

  // 8a. If you go to the dev tools you’ll see that we made 5 ducks, but they are all in the same place! Modify createDuck so 
  // each time it creates a duck, it appears in a random location. 
  // 8b. The ducks should also move to a random location after 1 second
  // HINT: Use Math.random() * window.innerWidth    for "left"
  //       And Math.random() * window.innerHeight   for "top"

  // 9. Our ducks are going to be easy targets if they only move once.
  //    Modify createDuck() so the ducks keep moving around!

  // 10. Well Done!  

   ——— Part 3:  We're almost there! —— 

  // 11. BOOM. Attach a "click" handler that adds the "shot" class to
  //     the duck when you click on it!

  // 12. After a duck has been clicked on, remove it from the DOM after
  //     a short delay (1 second)

  // 13. Create a new function named checkForWinner() that reads the DOM
  //     to see if there are any ducks left. If not, alert "YOU WIN!"

  // 14. BONUS: The ducks are moving pretty erratically, can you think
  //     of a way to adjust the ducks speed based on how far needs to move?

  // 15. BONUS: Add the "left" and "right" class to the duck based on the
  //     direction the duck is flying

  // FIN. You win 1 trillion tokens.  Play the day away!