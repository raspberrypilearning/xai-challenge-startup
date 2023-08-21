## What is AI and Machine Learning?

**Artificial intelligence** (AI) is a type of computing technology that helps machines perform tasks that typically require human-like intelligence. This can include things like recognizing speech, identifying objects in images and learning from data. Rather than giving machines human-like qualities, AI involves developing algorithms and systems that can process information and do things on their own, without needing humans to give step-by-step instructions.

You’ve probably done a bit of coding before, so you know programs are usually written: they are **rules-based**. Programs are a series of instructions and rules that the computer must follow exactly. `If this, then that.` 

Machine learning doesn’t work that way - it’s **data-driven**. Instead of using lots and lots of rules to cover every possibility, machine learning takes large amounts of data about a particular topic to build an ML model. The ML model is a representation of something. Usually the representation is of the real world, but it can also be of an imaginary context.

<div style='border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;'>
<h3>Example: Spotify Recommendations</h3>
All the songs on Spotify have been put into a big database, where each song not only has data about the artist, title and album, but also about how the song sounds. Each song has been analysed and has data attached to it for audio features (with values between 0 and 1) like:
<br><br>
<span style="color: #0faeb0">Danceability:</span> describes how suitable a track is for dancing! A value of 0.0 is least danceable and 1.0 is most danceable.
<br><br>
<span style="color: #0faeb0">Instrumentalness:</span> a prediction of whether a track contains no vocals. "Ooh" and "aah" sounds are treated as instrumental in this context. Rap or spoken word tracks like podcasts are clearly "vocal". The closer the instrumentalness value is to 1.0, the greater likelihood the track contains no talking at all.
<br><br>
<span style="color: #0faeb0">Speechiness:</span> a measure of the presence of spoken words in a track. The more exclusively speech-like the recording (e.g. talk show, audio book, poetry), the closer to 1.0 the speechiness value. 
<br><br>
Every time you listen to music on the service, the app takes note of how often you listen to each song and (if you rate music you listen to) how much you like it. Once the application has a certain amount of data about your choices, the model compares that data to all the songs in the database and <b>predicts</b> things that are similar to your tastes that you will probably <b>also</b> like.

</div>


It would be very difficult to make a series of rules to decide what music you might like in this way, and impossible to do it for all the users on the service. But with machine learning, it is possible to create a **classification predictive model** that can process user data and give us recommendations. Once the model has enough data on a single user’s choices, it can **predict** other things that fit the pattern of things that user may like.

**Recommendation algorithms** like this are incredibly popular among all kinds of companies for advertising and content streaming, but can you think of any other places you might see this kind of machine learning application suggesting things to you in your daily life?

--- task ---

**Think: Where have you seen technology recommending things you might like?** 

Fill in the first table in your blueprint document with your ideas now.

Chat with someone else to see if they have any other ideas - you might be surprised just how many recommendation algorithms you have seen!

--- /task ---

