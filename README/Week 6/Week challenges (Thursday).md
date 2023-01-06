# Strings

## **Solution:** 📋✔️🎊✨

```
function greet(name) {
return "Hello " + name + "!";
}

greet(name);
```

# String: length

## **Solution:** 📋✔️🎊✨

```
function length(str) {
  return str.length;
}
```

# String: toUpperCase()

## **Solution:** 📋✔️🎊✨

```
function toCase(str) {
  return str.toLowerCase() + "-" + str.toUpperCase();
}
```

# String: charAt()

## **Solution:** 📋✔️🎊✨
```
function shortcut(str0,str1) {
return str0.charAt(0) + str1.charAt(0);
}
```

# String: indexOf()

## **Solution:** 📋✔️🎊✨

```
function indexOfIgnoreCase(str0,str1) {
let str0Lower = str0.toLowerCase();
let str1Lower = str1.toLowerCase();
return str0Lower.indexOf(str1Lower);
}
```
