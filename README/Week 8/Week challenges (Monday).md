# Training JS #7: if..else and ternary operator!

## **Solution:** 📋✔️🎊✨
```
function saleHotdogs(n){
  if (n < 5 ) {
    return n * 100
  }
   else if (n < 10)  {
    return n * 95 
  }
   else if (n >= 10)  {
    return n * 90
  }
}
```

# Training JS #8: Conditional statement--switch

## **Solution:** 📋✔️🎊✨
```
function howManydays(month){
  var days;
  switch (month){
    case 1:
      days = 31;
      break;
      
    case 3:
      days = 31;
      break;
      
    case 5:
      days = 31;
      break;
    
    case 7:
      days = 31;
      break;
      
    case 8:
      days = 31;
      break;
      
    case 10:
      days = 31;
      break;
      
    case 12:
      days = 31;
      break;
      
    case 2:
      days = 28;
      break;
     
    default:
      days = 30
  }
  return days;
}
```

# Basic Calculator

## **Solution:** 📋✔️🎊✨
```
function calculate(num1, operation, num2) {
 switch (operation)
   {
       case "+": "Suma";
       return num1 + num2;
       break;
       
       case "-": "Resta";
       return num1 - num2;
       break;
       
       case "*": "Multiplicación";
       return num1 * num2;
       break;
       
       case "/": "División";
       return num2 != 0 ? num1/num2 : null;
       break;
       
       default: 
       return null;
   }
}
```
