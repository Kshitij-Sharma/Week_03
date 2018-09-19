# Week_03

# Javascript Fundamentals

### For Loops

For loops will start at a value and iterate through a range. 

```Javascript 
let introCourses = [125, 173, 225, 233, 241, 374]
for (let i = 0; i < introCourses.length; i++) { 
  console.log(introCourses[i])
}
```

### While Loops

While looks will continue till the condition is false. 

```Javascript 
let count = 1;
while (count < 10){
    console.log("Count " + count)
    count += 1;
}
console.log("Done counting")
```

### JSON

JSON is a way of storing different types of information in an object in javascript. 

```Javascript
let student = {
  name: "Aria",
  age: 20, 
  favoriteBobaPlaces: ["latea", "teamoji", "kung fu tea"],
  friends: [
    {
      name: "Alpri", 
      age: 19
    }
  ]
}

console.log(student.name)
console.log(student.friends[0].name)
```


## What does this do?

```Javascript

let student = {
  courses = []
}
let introCourses = [125, 173, 225, 233, 241, 374]

for (let i = 0; i < introCourses.length; i++) { 
    student.courses.push(introCourses[i])
}
console.log(student)
```


