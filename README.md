# grammar checker
In this project, you’ll use what you know about iterating over arrays to gather information and improve the quality of a paragraph.

# Tasks

**1** In main.js, the story variable holds the paragraph we’ll be editing. In order to edit the story, we turn it into an array on line 3. The .split() method separates the story string by the space character (' ') and stores each word as an element of the array.

To see the array we’ll be working with throughout the lesson, log storyWords to the console.

After you’ve viewed the storyWords array, comment out the console.log() statement before moving to the next task.

**2** For a better visual comparison of the original and edited stories, we want to view the edited storyWords array as a string. To change the storyWords array back into a readable string, we can invoke the .join() method on storyWords.

Give the .join() method an argument of an empty space character (' ') to separate each array element with a space in the string.

Place the .join() method invocation as an argument of a console.log() statement to log the final story to the console.

 ### Counting Words

**3** Now it’s time to start editing the story by manipulating the storyWords array. We want to be able to see the changes, so be sure your console.log() of the joined story is the last line of code in your editor.

First, above the console.log() statement that uses the .join() method, create a variable named count that stores the number 0.

Directly below count, use a .forEach() method to iterate over the storyWords array. As an argument of the forEach() method, create an empty function to be used as the callback function.

While ES6 arrow syntax is recommended for the callback function, feel free to use any syntax you’re comfortable with.

**4.** For each word in the storyWords array, we want the count variable to increment by one.

Add a parameter named word to the callback function of the .forEach() method to be used to store the current element when iterating over the storyWords array. Each time storyWord iterates, increment count by one.

Below the .forEach() method, log count to see how many words are in the story.

**5.** 
