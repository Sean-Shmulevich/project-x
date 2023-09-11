
## Main Ideas
1. History map. A way for users to view and access their history in the clearest possible way.
    - We could do user-created folders where they have conversations stored and they start new conversations from a central prompt, and the folders are autogenerated.
    - But I don't think that is the best idea.
2. Context should be portable. You should be able to tell it to remember something and when
3. We want to auto-determine where a question should go. put it into the right conversation or folder.
4.  Browser integrations make it easy to communicate with the internet. 
  - Turn the conversation topic into 10 best possible search results
  - Check the validity of Ai generated information against the internet.
  - Find a website and feed the content of that website to the AI to ask questions about it.
  - Automatically determine when a prompt should go straight to search results.

## Concrete idea of app flow
- When you open up a new convo, you either start from a new context, choose one
that you usually use, or choose one that you have created to do a specific
purpose. The brain structure comes in when you then zoom out to see your chat
history which is grouped into categories. we want to automatically know where
in your history a new question would go. In order to best categorize the
history we would probably need some deep learning models, seperate from chatGPT
language learning model

- You still ask questions in a linear chat but the context of the questions that
you ask isnt necessarily linked to that specific conversation thread. You can
either specify where it takes context from or it will automatically assume
based off of the topic you are promping about.

- The app still looks like agpt linear prompt but you can zoom out to see a graph
history of your questions that you ask. the graph is autogenerated

## Undeveloped idea: Programmable blocks of context 
- programmable blocks of context that you can bring into your chats at any specific moment to maybe perform some action on the data in the conversation.
for example, a programmable block that consists of just one prompt that says "Turn the conversation into a summary read by a rabbi" 
- or maybe take the data above and ask me some questions about it so that you can have enough data to generate some kind of graph or something

## Smaller potential ideas
1. Feeding formats to create new things. functions for GPT
2. The teacher needs to make a system for generating worksheets out of a textbook
3. The teacher can feed it that textbook and create a series of prompts that helps them generate the worksheets in a generative way.
4. Something that can turn data into flashcards and let you save them
5. Tab management system
6. Meta prompting/prompt actions. Use up to help you generate the best prompt possible by providing a list of actions you can do like generating a sequence of steps.
7. Zooming into information lets you visually interact with the response and zoom into information. So you highlight something, and you can automatically send a
prompt to clarify this specific concept that the user visually interacted with.

## The simpler, the better. 
## History visualized better is a huge value add for some people and for others not, the UX should be great

# Who needs it:
people who need GPT 
