# lloid
AI powered personal assistant

### The plan
Create an ai assistant who take commands such as scheduling appointments, sending messages and general ai queries using voice as the primary input.

Additionally the assistan will be able to obsorb saved voice or written conversations and offer reminders about past conversations when prompted.

### How to accomplish this goal
Spin up a set of docker containers that interact to provide the following:
1. a voice to text engine
2. a text to voice engine
3. a butler styled ai that takes input from the voice prompt and outputs commands to the background system to accomplish tasks
4. a historian system that holds past transcribed or uploaded text which can be searched by time, participant, or text.
5. an interface code system that helps the ai interact with oustside system, emails, calendars, sms, system controls, etc...