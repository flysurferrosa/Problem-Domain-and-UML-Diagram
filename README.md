The problem domain consists of the following: the class Deck object, which has an array of cards and a count function.  In our example we create an instance of Deck called d, which has an array of 52 cards, and this is created by initializing a Deck object according to the function init described in the Deck's properties.  We've also created the class of objects called Card, and Deck consists of zero or more Card obects, so we call this relationship Aggregate.  I created another Object class called Hand which also consists of zero or more Card objects, so this is also an aggregate relationship.  I created Player class of objects as well, and this object has name and order (player 1, player 2, etc.), as well as a card array associated with each player.  The game has two instances of Player object, player1 and player2.  The game also uses a few instances of the Hand object in pile, p1points and p2points.   