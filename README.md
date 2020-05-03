# CSP-Functions-with-Return-Values
Practice . 15.6
console.log("Limiting 5 to the range 10 - 20: " + constrain(5,10,20));
console.log("Limiting 10 to the range 10 - 20: " + constrain(10,10,20));
console.log("Limiting 15 to the range 10 - 20: " + constrain(15,10,20));
console.log("Limiting 20 to the range 10 - 20: " + constrain(20,10,20));
console.log("Limiting 25 to the range 10 - 20: " + constrain(25,10,20));

// Rewrite this function to use the pattern described and a single return value

var check;
function constrain(input, low, high){
  if (input < low) {
    check = low;
  } else if ((input > high)) {
    check = high;
  } else {
    check = input;
  }
  return check;
}
