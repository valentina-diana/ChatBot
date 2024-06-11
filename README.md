# ChatBot
The chatbot is built on the Pandorabots platform and can interact with users in Romanian, assisting them in understanding grammar through interactive conversations.

## Features

### Greetings and introduction:
- The bot greets users and asks for their name.
- It stores and reminds users' names for personalized interactions.

### Grammar lessons:
- Teaches the flexible parts of speech in Romanian, including nouns, pronouns, and verbs.
- Provides definitions, classifications, and examples.
- Interactive buttons for users to choose what they want to learn next.
  
### User interaction:

- Users can introduce themselves in various ways (e.g., "My name is", "I am", etc.).
- The bot can memorize and recall the user's name.
- Provides options to learn more or to change the topic through button prompts.

## Structure of AIML

### Categories: 
Each interaction is defined within <category> tags, specifying the pattern and corresponding response template.

### Buttons and postbacks: 
Utilize <button> and <postback> for interactive options.

### Memory and recall: 
Use <set> and <get> to store and retrieve user information.

