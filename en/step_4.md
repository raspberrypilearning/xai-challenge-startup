## Play with predictive AI

In this step, you will explore some predictive AI applications on the internet and investigate how they work. 

--- task ---

First, have a play with the Thing translator by [clicking this link](https://thing-translator.appspot.com/){:target="_blank"} (you’ll need a computer or device with a camera - if you don’t have one, you can skip to the next task). 

While you’re taking pictures of things, think about these questions and write the answers in your **blueprint**:

1. What is the application doing? What clues can you see on the screen?

2. How do you think the application works to output/ produce these predictions?

--- /task ---

--- task ---

Once you’ve had enough of the Thing Translator, have a play with an AI powered game called Quick Draw by [clicking this link](https://quickdraw.withgoogle.com/){:target="_blank"}. (You can use your mouse or trackpad to draw.)

While you’re drawing, think about these questions and write the answers in your **blueprint**:

1. What is the application doing? What clues can you see on the screen?

2. How do you think the application works to predict what you are trying to draw?

--- /task ---

--- task ---

Watch the [Video about Quick Draw](https://youtu.be/X8v1GWzZYJ4){:target="_blank"} now, to see the designers of the game explain what it does, and have a look through the [Quick Draw image dataset gallery](https://quickdraw.withgoogle.com/data){:target="_blank"} to see what thousands of other people drew!

--- /task ---

<p style='border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;'>
<span style="color: #0faeb0">It is important to remember that the model isn’t thinking or making choices</span> - it’s just processing the pixel data of the images and examining that information to detect patterns.

</p>

Each one of those example images will be stored in the model’s training data as part of a **class**. When it is comparing your image to the examples it has been trained on, the model is measuring how closely your image fits the pattern it has detected in each class, and this is what it predicts - the level of certainty that your **sample data** should be in this class. 

Because of this, **the more and wider examples of training data you can train the model with, the more certain it can be that the sample fits a particular class**.

### Think about: Bias

While more training data is *usually* better, we have to be careful that the way we are training the model isn’t influenced into being unfair or wrong by the data selected. This unfair influence on the machine learning model is called **bias**, and it’s really important that we don’t get it wrong. The impacts of bias in artificial intelligence can have really big negative effects on society when systems make wrong or unfair decisions for people.

But that’s enough talking for now - let’s make your first ML model!
