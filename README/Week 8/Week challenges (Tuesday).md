# Even or odd

## **Solution:** 📋✔️🎊✨
```
function evenOrOdd(number) {
  var number;
  
  if (number %2 == 0){
    return "Even";
  } else {
    return "Odd";
  }
}
```

# A wolf in sheep's clothing

## **Solution:** 📋✔️🎊✨
```
function warnTheSheep(queue) {
var wolf = queue.indexOf("wolf");
  if (wolf === queue.length - 1){
    return "Pls go away and stop eating my sheep";
  }
  var sheep = queue.length - (wolf + 1);
  return "Oi! Sheep number " + sheep + "! You are about to be eaten by a wolf!";
}
```
