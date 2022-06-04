# Project 1
## p1-random.js
/*
    CIT 281 Project 1
    Name: Sujala Chittor
*/
// Returns a random number between min (inclusive) and max (exclusive)
function getRandomInteger(min, max) {
    //let min = 5;
    //let max = 25;
    let RandomInteger = Math.floor(Math.random() * (max - min) + min);
    return RandomInteger
}


function generateRandomLetter() {
    let alphabet = "abcdefghijklmnopqrstuvwxyz";
    //let part = str.slice
    //let i = alphabet.charAt(getRandomInteger(0, alphabet.length));
    let randomstr = "";
    let ln = getRandomInteger(5, 26);
for (let i = 0; i < ln; i++ ){ 
  randomstr = randomstr + alphabet.charAt(getRandomInteger(0, alphabet.length));
  //console.log(randomstr);
  } 
  console.log(ln, " ",randomstr);
}
generateRandomLetter();

## p1-date.js
/*
    CIT 281 Project 1
    Name: Sujala Chittor
*/
console.log((["Sunday","Monday","Tuesday","Wednesday","Thursday","Friday","Saturday"][(new Date()).getDay()]));

  


  





