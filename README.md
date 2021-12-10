# [Movie Seat Booking](https://lana-20.github.io/MovieSeatBooking/)

In this application I'm building a UI that you'd see in a movie theater website, where you can pick your seat and your movie.
I have a movie with a price. Each movie has a different ticket price.
I have a legend that shows that blue is Selected, white is Occupied, and grey is Open.
I can select some movie seats. I can't select the occupied ones. 

Below the seat chart it says "You have selected 4 seats for a price of $40", because each ticket is $10 for this movie.
If I go ahead and change the movie to Matrix Resurrections, which is $12, it updates the total to $48.
I can deselect the seats as well.

I'm also implementing Local Storage so that the indices of the seats, the movie and the price get saved so that it stays on the page after a reload.
I'm saving everything in local storage and then populating the UI with that data, so that when I come back to the page it's still there.
So, I'm working with local storage, some high order array methods like forEach() and map(), and the spread operator.

