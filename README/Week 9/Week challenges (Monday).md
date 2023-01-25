# "this" is a problem

## **Solution:** 📋✔️🎊✨
```
function NameMe(first, last) {
    this.firstName = first;
    this.lastName = last;
    return this.name = this.firstName + ' ' + this.lastName;
}
```

# Thinkful - List and Loop Drills: Lists of lists

## **Solution:** 📋✔️🎊✨
```
function processData(data){
  return data.reduce((a, [b, c]) => a * (b - c), 1)
}
```

# Stop gninnipS My sdroW!

## **Solution:** 📋✔️🎊✨
```
function spinWords(sentence) {
  let words = sentence.split(" ");

  for (let i = 0; i < words.length; i++) {
    if (words[i].length >= 5) {
      words[i] = words[i].split("").reverse().join("");
    }
  }
  return words.join(" ");
}
```
