TIC TAC TOE(2025)

WINNING PATTERN:
HORIZONTAL: [0,1,2] [3,4,5] [6,7,8]
VERTICAL: [0,3,6] [1,4,7] [2,5,8]
DIAGONAL: [2,4,6] [0,4,8]

Create a container for the whole game <div class="container> </div>
create a new "class="game" with "9" buttons(which represents 9 boxes) in the table shape <div class="game"> </div>

Use Coolor to style the css.

vh= viewport height(70%)
it is a dynamic height, to reserve 70% of webpage height of the complete webpage wherever it is either mobile/laptop.

vmin= 60% of 70% - for game class

vmin= 18% of 60% of 70% - for box class

display:flex - to display items in only a row without wrapping to the next row, flex items shrink to fit in one line, even if they get very small.(BUT ITEMS DON'T WRAP)
flex-wrap: wrap - if the items are shrinking too much, they will be moved to next row.

Why is flex-wrap: wrap; not in the .container?
Because .container only has one direct child, which is the .game element.

gap: gap between each button 





