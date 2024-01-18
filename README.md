# Flatdango-Challenge

An app that allows a user to purchase movie tickets from the theater.

To run the application:

- First run:

        json-server --watch db.json  in terminal 


This ensures our db.json file is running in the backend.


Live Site: https://bradleymbuvi.github.io/Flatdango-Challenge/


Core Deliverables:
As a user, I can:

1. See the first movie's details, including its **poster, title, runtime, showtime, and available tickets** when the page loads. The number of available tickets will need to be derived by subtracting the number of tickets sold from the theaters capacity.

2. See a menu of all movies on the left side of the page in the `ul#films` element when the page loads.

3. Buy a ticket for a movie. After clicking the "Buy Ticket" button, I should see the number of available tickets decreasing on the frontend. I should not be able to buy a ticket if the showing is sold out (if there are 0 tickets available). **No persistence is needed for this feature**.

4. Click on a movie in the menu to replace the currently displayed movie's details with the new movie's details.

5. When a movie is sold out (when there are no available tickets remaining), indicate that the movie is sold out by changing the button text to "Sold Out". Also update the film item in the `ul#films` menu by adding a class of `sold-out` to the film. 



Author : Bradley Mbuvi