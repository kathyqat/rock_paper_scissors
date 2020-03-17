# rock_paper_scissors

This project is for making a playable rock-paper-scissors game in the browser console with Javascript. It will later have a front end component. From The Odin Project's (TOP) [Full Stack Development](https://www.theodinproject.com/courses/web-development-101/lessons/rock-paper-scissors) course.

Codepen link: https://codepen.io/kathyqat/pen/KKpRoaq

I've noticed that JavaScript is ok with having extremely wordy names compared to C++. It also prefers to not use global variables and to have readability over brevity. Having learned C++ first, I have to get used to the minorly different coding practices.

Head-scratchers:
1. console.log() first outputs undefined, then outputs the desired value. I looked it up to see why, apparently it does that because "a variable declararion does not produce a value so again undefined is printed to the console."
2. I copied TOP's code, as recommended, to test playRound(). But it did not work until I edited the snippet to make computerSelection a callback function. The variable should've been able to store the return value of computerPlay(), but it didn't for some reason.
3. Received SyntaxError: await is only valid in async functions and async generators. It looks like asynchronous functions are a more advanced topic, so I was unable to make the code wait before executing the next line. I vaguely remembered being able to do that in C++.

Copied code: I searched up how to get a random number between two values. The function getRandomInt() is from the Mozilla Developer Network's article on the Math.random() function. I did think enough to remove the second Math.floor(), because I am using an integer argument anyway. TOP references to many MDN articles, which makes me have a newfound appreciation for Mozilla.