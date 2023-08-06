# Random-joke-generator

Today we are going to create a random joke generator. For this, we are going to use HTML, CSS and Javascript.
The HTML code consists of a wrapper that encloses other elements. Inside the wrapper, we have, a laughing emoji. I have used the Unicode of laughing emoji – &128514 This emoji is wrapper inside a span element. Following the span is the p element where the joke is displayed. Lastly, we add a button with the id btn. The button consists of text – ‘Get Random Joke’.

The CSS styles used here are pretty basic and self-explanatory. We make the usual CSS reset to remove the unwanted paddings and margins. For the background color with use #fab22e. We add dimensions to the wrapper. The wrapper is made 80vmin wide. Using the absolute position and translate we centre the wrapper. To make it stand out even more we add some box shadow to it.

Next, we add functionality to this generator using Javascript. Now copy the code below and paste it into your javascript file.

We get the button and paragraph button and assign them to variables. Next, we create a constant and the API URL to it. I am using the Joke API by Sv443. We fetch and get a JSON response. This response is a JSON object. We need the joke key from this object. We extract the value of the joke key and display it in the p element.
Next, we add a click event to the button so that the getJoke function is run on every button click. And that’s it. Your joke generator is now ready. Go ahead and customize it the way you want.
