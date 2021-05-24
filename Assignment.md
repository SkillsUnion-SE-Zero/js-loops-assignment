[<img src="assets/images/su-logo.png" alt="Skills Union Logo" height="80px" />](https://www.skillsunion.com/)

# JavaScript Loops: Assignment

## Problems

### 1: Multiplication Tables

1. Write a `for` loop that will iterate from `0` until `10`.
1. For each iteration of the `for` loop, it will multiply the number by `9` and log the result (e.g. `"2 * 9 = 18"`).

console.log("starting loop ...");
**Bonus:**

- Use a nested for loop to show the tables for every multiplier from 1 to 10 (100 results total)

````js
// Your Answer
`console.log("starting loop ...");

for (let i = 0; i < 11; i++) {
console.log(i * 9);
}
console.log("Ending loop ...");``



### 2: The Grade Assigner

Check the results for every value from 60 to 100 - so your log should show "For 89, you got a B. For 90, you got an A.", etc.

```js
// Your Answer
for (let i = 60; i < 101; i++) {
  console.log(i);

  if (i === 89) {
    console.log("you got a B");
  }
  if (i === 90) {
    console.log("you got an A. ");
  }
}```

### 3: Favorite TV Shows

1. Create an Array to hold your favorite TV shows
1. For each show, print to the console a string like:

   <!-- ```
   My #1 choice is Person of Interest
   My #2 choice is Battlestar Galactica
````

```js -->
//Your Answer
const favoriteTvShows = [
  "Desmonds",
  "BBC New",
  "Telekoma",
  "Giving Time",
  "Akuna Matata",
  "TINSEL"
];

for (let i = 0; i < favoriteTvShows.length; i++) {
  console.log(favoriteTvShows[i]);

  if (i === 0) {
    console.log(`My Number 1 choice is ${favoriteTvShows[0]}`);
  }
  if (i === 3) {
    console.log(`My Number 2 choice is ${favoriteTvShows[3]}`);
  }
}
```

### 4: Age Filter

1. Create an Array to hold a list of ages
1. Loop through and log only the ages that are over 21

```js
// Your Answer

const studentsAge = [35, 25, 27, 40, 21, 36, 19, 20];

for (let i = 0; i < studentsAge.length; i++) {
  if (studentsAge[i] > 20) {
    console.log(studentsAge);
  }
}
```

## Optional Bonus Problems

### 1: The even/odd reporter

Write a for loop that will iterate from 0 to 20. For each iteration, it will check if the current number is even or odd, and report that to the screen (e.g. "2 is even").

```js
// Your Answer
```

### 2: Change Odd Numbers

Change all **odd numbers** in the Array to their value multiplied by 2:

```js
const numbers = [4, 9, 7, 2, 1, 8];

// Your Answer

console.log(numbers); // => [4, 18, 14, 2, 2, 8]
```

## Submission Guidelines

- Cite any relevant sources consulted during your research
- Solve the problems using your own code
- Do not copy and paste solutions from the source material
