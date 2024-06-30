# 100 Days Of Code - Log

### Day 1: June 25, 2024


**Today's Progress**: Completed reading the JS Documnetation on the CodeHelp website. Started practicing JS on FreeCodeCamp and completed my first project of a Pyramid Generator.

**Thoughts:** I'm getting a hang on the JS syntax and functionalities

### Day 2: June 26, 2024

**Today's Progress**: Solved 3 questions on LeetCode on practice JS for 30days section, completed the pyramid generator officialy, practiced JS functions by creating a gradeBook app in freeCodeCamp, Creating a project called RPG - Game. Continued the RPG game building and its getting lengthy now. Completed the game now!

**Thoughs**: I'm getting a hang on the JS backend functionalities I think so and I'm feeling that I've accomplished something".

**Links** [text](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures-v8/#learn-basic-javascript-by-building-a-role-playing-game)


### Day 3: June 27, 2024

**Today's Progess**: Solved two leetCode problems on setTimeout(() => {},t) functions. Completed Basic Debugging by Building a random background-color generator on freeCodeCamp website. Completed a Calorie Counter Web Application by using HTML,CSS and JS.

**Thoughs**: The LeetCode problems were very easy and the descriptions were really confusing and it was difficult to understand them clearly, so I took the help of discussions and they solved the issue of my confusion. After completing the Calorie Counter App I've learned a few things: 1. about the "selected" property of the <select> HTML element. It selects the option with that attribute as default one.<br/>
2.Learned a lot about Regex, it is a short for Regular Expressions, It is used to recognize patterns in strings, it has the syntax of const regex = /+-\s/g; This is used to find strings like this: "+- Hello" or "+- Bye" but not strings like "+Hello". To do that we have something called Character Classes we can add to the regex, regex = /[+-\s]/g. This can detect strings like "+hello", The "g"in the regex performs a global match meaning it keeps on finding the patterns even after a match. Similarly there is another thing like this <br/> regex = /[+-\s]/i, the "i" here makes the regex match patterns case-insensitively.
<br/>
3. String.replace() method. It takes two arguments - .replace(regex or a string to find, string to replace it with);
4. const regex = /[0-9]/g, this recognizes and matches all strings with a single digit. To match multiple digits, we use /[0-9]+/ after the character class. Instead of writing /[0-9]+/ we have a shorthand like this /\d+/g. This can match all strings which have any number in them.
<br/>
5.String.match() method. It takes a regex as an argument and returns an array of the matched results. <br/>
6. Regarding DOM: element.insertAdjacentHTML(position,HTML to add); <br/>
7. .alert() function, which is a built-in function of a browser and it is used to display whatever is passed into it as an alert or a pop-up. </br>
8. Array.from(array-like) method. I used this to create an array from a NodeList. document.querySelectorAll() returns a NodeList, which is an array-like. so the method takes a NodeList and returns an array with the elements of NodeList as array elements

### Day 4: June 28, 2024

**Today's Progress**: Completed a Rock,Papers and Scissors Game with the help of JS in freeCodeCamp. Link to the same --  
[ https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures-v8/ #review-dom-manipulation-by-building-a-rock-paper-scissors-game] <br/>

Solved 1 LeetCode problem, Participated as a virtual participant in CodeForces contest 900 something. Did two quesitons and 1 got accepted and the other one got Time Limit Exceeded error. Started creating the rock paper scissors game on my own. 

### Day 5: June 29, 2024

**Today's Progress**: Completed the rock paper scissors game. Learned about Object.keys() method that takes an array-like or object-like and returns an array with keys of an object if an object is passed and array-elements if an array is passed. Started a MP3-player project using JS in freeCodeCamp and its damn confusing man. Its eating my head. I learned a lot of things today. <br/>
1. Promise.race(array-like) - its a method that returns the fastest promise
2. Object.keys(array-like or object) - it is amethod that returns the keys of an object and elements of an array in the form of a new array.
3. There is something known as WebAudioAPI which is used to play-pause-shuffle and do other operations on songs.
4. Had a revision of the spread Operator. It creates a shallow copy.
5. had a revision of the array.map() method, it takes a callBack function as argument and returns a new array according to the callBack fucntion passed;
6. array.join() method - it takes a separator as an argument. It returns a string which is form by concatenation of all array elements with the separator after each element.
7. array.sort() method. It sorts the array in ascending order alphabetically. What about numbers then? It converts all elements of the array into strings first and then compares them according to UTF-16 encoding. 
8. array.find() method - it takes a callBack function as an argument and returns the first element that matches according to the function. It returns undefined it no such element is found. 
9. There is something called the audio currentTime that is sued to set the duration of the song.
10. There is also something called audio.pause() that is used to pause the song.
11. forEach() method. It takes a callBack function as argument and for each element of the array it does what the function tells it to do. 
12. There is a .setAttribute() method, .removeAttribute() method, classList.add()/remove() methods.

### Day 6: June 30, 2024

**Today's Progress**: Completed the MP-3 player project in freeCodeCamp. Completed making a date Formatted and a new Palindrome checker from scratch using JS.

**Thoughs**: I don't know what I did in that project but well its completed now. freeCodeCamp is a good website because it provides you with a lot of projects but its not like you've got to do everything on your own, it provides you with certain things that I think that is what makes you feel that you're not doing everything by yourself so you must be cheating and it does feel that way now. Now I feel a little confident in JS and its structure. I think I'm able to think properly about the functionality now.

**Link** :  https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures-v8/#learn-basic-string-and-array-methods-by-building-a-music-player