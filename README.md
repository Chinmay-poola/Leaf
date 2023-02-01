# Leaf
It's an AI based chatbot which works on discord.

model.py is the AI behind the bot.
main.py is the discord development. 
Intents.json is the dataset which I found on kaggle. I have added a lot more data into this file. Please feel free to add more data and make sure it's appropriate else the bot could give faulty responses. 

Data set was a jason file and not a csv file which made storing the classes responces and inputs in a single file with the most optimal memory and handling.
I first created a file or a variable which is a bag of words which have been lemmatised and processed.  
I used a sequntial model, which is a deep learning neural network. Sequntial model works with exactly one input tensor.
To train the data I used two vectors (one for the input and second was the classification). The sentence and it's class. For the sentence I used the bag of words to make the vector. The class vector was just based on order. 
Once the model was trained. The data had premade responses for each class. We can then return a random response for a given text. 
With it's vast API, Discord was the best platform to test this bot. Discord's usage has been skyrocketed in the past few years and has a well connected community. With discord this bot can reach millions of people. 

This bot can have more future updates like playing music and some mini games and so much more!
