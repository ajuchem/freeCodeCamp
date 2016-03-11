## freeCode Camp Golf Code Challenge

### Instructions

In the game of golf each hole has a ```par``` for the average number of ```strokes``` needed to sink the ball. Depending on how far above or below ```par``` your ```strokes``` are, there is a different nickname.

Your function will be passed ```par``` and ```strokes``` arguments. Return the correct string according to this table which lists the strokes in order of priority; top (highest) to bottom (lowest):


| Strokes       |  Return       |
| ------------- |:-------------:|
|     1         | Hole-in-one!  |
| <= par - 2    | Eagle         |
|    par - 1    | Birdie        |
|    par        | Par           |
|    par + 1    | Bogey         |
|    par + 2    | Double Bogey  |
|    par + 3    | Go Home!      |


Remember: ```par``` and ```strokes``` will always be numeric and positive.
