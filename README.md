# Chatbot-using-Rasa-NLU-and-Rasa-Core
The bot will show you the weather of a location provided in the message for the bot.

# To train NLU model
 1. Train the model by using 
```rasa train nlu```
2. After training - run 
```rasa shell nlu```

# To train the dialogue model
1. To run custom action server by running:
```rasa run action```
2. Keep the server running and open a new terminal and train the rasa core model by running:
```rasa train```
3. Talk to the chatbot once it's loaded after running:
```rasa shell```

# Start manually training model through interactions
1. Make sure the custom action server is running by
```rasa run actions```
2. Now start the interactive training session by running
```rasa interactive```
3. These interactions will be saved in stories.md file
