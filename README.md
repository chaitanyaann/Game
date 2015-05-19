# Game
var dragon = prompt("You're walking through a dungeon, minding your own business, and you run into a dragon! Do you FIGHT him, run away from him, or hide?").toUpperCase();

switch(dragon) {
  case 'FIGHT':
    var strong = prompt("How courageous! Are you strong (YES or NO)?").toUpperCase();
    var smart = prompt("Are you smart?").toUpperCase();
    if(strong === 'YES' || smart === 'YES') {
      console.log("You only need one of the two! You beat the dragon--nice work!");
    } else {
      console.log("You're not strong OR smart? Well, if you were smarter, you probably wouldn't have tried to fight a dragon. You lose!");
    }
    break;
  case 'Hide':
    var hide = prompt("All right, we'll hide away. Do you no where (YES or NO)?").toUpperCase();
    var trees = prompt("Do you hide in trees").toUpperCase();
    if(money === 'YES' && dollars === 'YES') {
      console.log("Great! You escaped.");
    } else {
      console.log("Dang! This dragon killed you");
    }
    break;
  case 'RUN':
    var fast = prompt("Let's book it! Are you fast (YES or NO)?").toUpperCase();
    var headStart = prompt("Did you get a head start?").toUpperCase();
    if(fast === 'YES' || headStart === 'YES') {
      console.log("You got away--barely! You live to stroll through the dungeon another day.");
    } else {
      console.log("You're not fast and you didn't get a head start? You never had a chance! The dragon eats you.");
    }
    break;
  default:
    console.log("I didn't understand your choice. Hit Run and try again, this time picking FIGHT, Hide, or RUN!");
}

