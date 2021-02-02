# BotAssistance

Task:
1.  Build a chatbot using the Rasa framework (version: 1.9.3)
2.  Chatbot should include one form with the following slots:
       a) Name
       b) Phone Number
       c) Email Address
3.  All the slot values should be stored in a database (any database) along with the sender_id.
4.  The name slot should be extracted from the entity (accuracy >= 90%)
5.  You can use regex or any other library for extracting phone numbers and email addresses.
6.  The chatbot should consist of a few FAQs. Use the response selector component for the FAQs.
7.  The chatbot should reply with generic intents: greet, goodbye, who are you, what can you do for me, etc.
8.  Connect the chatbot to any one of these channels:
      a) WhatsApp
      b) Facebook
      c) Web
9.  There should be no grammatical errors in the utterances.
10. All the utterances should be mentioned in the domain.yml file




As mentioned in the task I could not use Rasa framework 1.9.3 due to issues in my anaconda, there was continous errors due to dependancies. I had tried debugging it for long then proceeded with version 2.0
As mentioned I have used the slots such as phone numbers,name, email address, intents, utterance forms etc

Challenges faced:
After debugging I could train my Rasa model with used slots intents and utterances.
As my rasa environment crashed suddenly and it could not proceed with the connectors

I am still working and hoping to get the bot connected to a connector soon.
