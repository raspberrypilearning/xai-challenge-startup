## Play with predictive AI

In this step, you will explore some predictive AI applications on the internet and investigate how they work. 

--- task ---

First, have a play with **Dictation.io** by [clicking this link](https://dictation.io/speech){:target="_blank"} (you’ll need to give your browser permission to use your microphone - if you don't have one, you can skip to the next task). 

Click the blue **Start** button to start the application. While you’re dictating things, think about these questions and write the answers in your **Blueprint**:

1. What is the application doing? What clues can you see on the screen?

2. How do you think the application works to output/ produce these predictions? Can you trick it?

--- /task ---

--- task ---

Once you’ve had enough of dictation, have a play with an AI-powered game called **Quick, Draw!** by [clicking this link](https://quickdraw.withgoogle.com/){:target="_blank"}. (You can use your mouse or trackpad to draw.)

While you’re drawing, think about these questions and write the answers in your **Blueprint**:

1. What is the application doing? What clues can you see on the screen?

2. How do you think the application works to predict what you are trying to draw?

--- /task ---

--- task ---

Watch the [video about Quick, Draw!](https://youtu.be/X8v1GWzZYJ4){:target="_blank"} to see the designers of the game explain what it does, and have a look through the [Quick, Draw! image data set gallery](https://quickdraw.withgoogle.com/data){:target="_blank"} to see what thousands of other people drew!

--- /task ---

<p style='border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;'>
<span style="color: #0faeb0">It is important to remember that the model cannot think or make choices</span> - it just processes the pixel data of the images and uses that information to detect patterns.

</p>

Each one of those example images will be stored in the model’s training data as part of a **class**. When it compares your image to the examples used to train it, the model measures how closely your image fits the pattern it has detected in each class, and this is what it predicts - the level of certainty that your **sample data** should be in this class. 

Because of this, **the more and wider examples of training data you can train the model with, the more certainty it will show that the sample fits a particular class**.

### Think about: Bias

While more training data is **usually** better, we have to be careful that the way we are training the model isn’t influenced into being unfair or wrong by the data selected. This unfair influence on the machine learning model is called **bias**, and it’s really important that we don’t get it wrong. The impacts of bias in artificial intelligence can have really big negative effects on society when systems make wrong or unfair decisions for people.

But that’s enough talking for now - let’s make your first ML model!
