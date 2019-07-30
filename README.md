# Alexa-Hindi-Skill
<h1>A beginner's guide to developing an Alexa Hindi Skill </h1>
<p> Alexa Hindi Skill has recently been launched to target a wider audience and knowing how to build one in Hindi is essential for better marketing </p>
<p> This repository guides you how to build a trivia game of chess using the Hindi language and if you're new to ASK a whole new realm is revealed to you. So, wacth closely as the closer you look the less you'll see. </p>
<p> Let's dive into it. Fisrt, you need an Amazon Alexa Developer account. You can create one easily. Next, you need to have an AWS account to run your code. </p>
<p> Create a new skill and enter the name this should be the same as your Invocation name which is the word that will activate your skill. Follow the selected options and then you need to build the Intents which are keywords that will generate responses. Select the language as Hindi.</p>
  <ul> Set Invocation name for your skill </ul>
  <li> Select the “Invocation” tab.</li>
  <li> Enter “ शतरंज” in the “Skill Invocation Name” field.</li>
  <ul> To create a custom intent we need to: </ul>
    <li> Click the “Add” sign near the “Intents” tab. </li>
    <li> Select “Custom Intent”. </li>
    <li> Enter “playerBio” in the field below. </li>
    <li> Click the “Create custom intent” button. </li>
  <ul> To create an utterance: </ul>
   <li>Select the “playerBio” tab.</li>
   <li>Enter the utterance text in the “Sample Utterances” filed in the form of “मुझे बताओ {player}”.</li>
   <li>Create a new slot in the window, which pops up when “{}” is entered, by entering “player” in the “Create a new slot” field    and by clicking the “Add” button. </li>
   <li>Click the “plus” sign at the right end of the “Sample Utterances” field.</li>
   <li>Click the “Add” sign within the “Slot Types” tab.</li>
   <li>Select “Create custom slot type”.</li>
   <li>Enter “playerNames” in the field below.</li>
   <li>Click the “Create custom slot type” button.</li>
   <li>Select “Slot Types” tab.</li>
   <li>Enter the names in the “Slot Values” field.<li>
   <li>Add names to the slot type by clicking the “plus” sign at the right end of the “Slot Values” field. Four names should be inserted: Bobby Fisher, Mikhail Tal, Jose Raul Capablanca and Garry Kasparov.</li>
   <li>Select the “player” tab.</li>
   <li>Choose the “playerNames” type from the “Slot Type” list.</li>
   <li>Click the “Add” sign near the “Intents” tab.</li>
   <li>Select “Use an existing intent from Alexa’s built-in library”.</li>
   <li>Enter “NoIntent” in the search field.</li>
   <li>Click the “+ Add intent” button.</li>
<p> The python code is in the reopsitory copy and paste in in the AWS Lambda console.</p>
<p> Now the skill has been built and we need to test the skill which can be done using the console. That's it! you are good to go. </p>
    
