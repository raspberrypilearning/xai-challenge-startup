## What is AI and machine learning?

**Artificial intelligence** (AI) systems are a type of computing technology that enables machines to execute tasks that typically require human-like intelligence. This includes tasks like recognising speech, identifying objects in images, and processing vast amounts of data autonomously. AI systems process large amounts of data to perform complex tasks; they do NOT replicate human intelligence.

If you have some experience with coding, it's likely that you've used a **rules-based** approach. That means you've provided the computer with a specific set of instructions it must follow exactly: `If this, then that.` 

However, machine learning (ML) doesn't work that way — it's **data driven**. Instead of using lots and lots of rules to cover every possibility, machine learning takes large amounts of data about a particular topic to build an ML model. The ML model detects patterns in that data to create a representation of something in the physical world.

<div style='border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;'>
<h3>Example: Digital plant identifier</h3>
Imagine you're on a nature walk and you come across a plant you've never seen before. You're curious to know what it is. With a digital plant identifier, you can snap a photo of it, and the app will predict what plant it is!
<br><br>
<span style="color: #0faeb0">Leaf shape:</span> The model might look for specific patterns or shapes commonly found in certain plants. Long and thin or broad and open? One frond or multiple?
<br><br>
<span style="color: #0faeb0">Flower colour:</span> Bright red? Soft purple? The hue might give away the plant's identity.
<br><br>
<span style="color: #0faeb0">Size and height:</span> Some plants are tall, others are short. This can be another clue.
<br><br>
When you upload a picture to the app, it uses the patterns in its trained model to find similarities with your photo data. It matches your photo data to the closest resemblance and classifies this as the most likely plant.

</div>

It would be a colossal task to manually craft rules to identify every single plant. But with machine learning, it's possible to develop an **image classification model** that uses pictures to classify various plant species.

For example, imagine you have a big box of cards, and each card has a picture of a plant on it. At first, you might not know which plant is which. But if you look at enough cards and someone tells you the name of the plant on each one, you'll start to notice differences between them, like the shape of the leaves or the colour of the flowers.

An image classification model does something similar. It processes lots and lots of pictures of plants, and it detects patterns in the data to identify the differences between plants. So, when you input a new picture of a plant, the model can compare that image data with all the other data it has processed before and determine the most likely type of plant that image represents. It's like a quick game of "match the card" every time it processes a new photo.

Can you think of other scenarios where machines need to classify inputs into categories, or recognise specific things in your daily life? (**Hint:** Not all systems use pictures! Some ML models detect different sounds or voices, some use written words, and others use numbers and information about things like the weather!)