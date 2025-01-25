# Portfolio-Project-Mixed-Messages

This project is a simple Random Message Generator implemented in JavaScript. It generates a random inspirational quote from the popular anime One Piece. Each time the program is run, it selects a random message from a predefined list and outputs it to the console.

## Features

+ A collection of 10 motivational quotes from One Piece characters.
+ Generates a random quote every time you run the program.
+ Simple and easy-to-understand JavaScript implementation.

## Code

The program uses an array named mixedMessages to store a collection of quotes:

```javascript 
const mixedMessages = [
  "'If you don't take risk, you can't create a future.' - Monkey D. Luffy",
  "'No matter how hard or impossible it is, never lose sight of your goal.' - Monkey D. Luffy",
  "'What good are your happy ideals if you can't do anything to make them a reality?' - Crocodile",
  "'You can't see the whole picture until you look at it from the outside.' - Trafalgar Law",
  "'If you're too afraid of making mistakes you won't be able to do anything.' - Sanji",
  "'When the world shoves you around, you've just got to stand up and shove back. It's not like somebody's going to save you if you start babbling excuses!' - Roronoa Zoro",
  "'I devoted my entire life to becoming the World's Greatest Swordsman. I made my choice, so I'm the only one who gets to call me stupid.' - Roronoa Zoro",
  "'When you aim high, you often come across fights that just aren't worth fighting.' - Marshall D. Teach",
  "'If I give up now, I'm going to regret it.' - Monkey D. Luffy",
  "'I am going to be the Pirate King!' - Monkey D. Luffy"
];
```

## Random Message Function

The randomMessageGenerator function randomly selects and returns a quote from the mixedMessages array:

```javascript
const randomMessageGenerator = () => {
  const randomMessage = mixedMessages[Math.floor(Math.random() * mixedMessages.length)];
  return randomMessage;
};
```

## Output to Console

Finally, the program logs the random message to the console:

```javascript
console.log(randomMessageGenerator());
```

## Example Output

```javascript
'No matter how hard or impossible it is, never lose sight of your goal.' - Monkey D. Luffy
```

## Technologies Used

+ Language: JavaScript (ES6+)

Date: 1/24/2025
