<h1>The Oracle - RPG Character Selection Chatbot</h1>

 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

<h2>Description</h2>
This project is an interactive RPG chatbot built using Node-RED that guides users through a decision-making process to determine if they will be allocated as a Mage or a Warrior. By engaging with an oracle-style chatbot, users are presented with a series of choices that reflect their preferences and personality, ultimately leading to their role selection. The chatbot provides an immersive, dynamic experience where each interaction influences the user's fate within the RPG world.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Node.red</b>
- <b>PHP</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Launch the utility: <br/>
In this flow, a user identification node is used to personalize the experience, ensuring that the chatbot recognizes and tailors the interaction to the user’s responses. Following this, a question node is introduced to verify if the user is ready to proceed with the adventure. If the user does not respond within a designated time (timeout), they are automatically redirected to the finish node, gracefully ending the interaction.
<img src="https://imgur.com/q9Ox3e4" height="80%" width="80%" alt="RPG_Class_Chatbot"/>
<br />
<br />
Jorney starts, first interaction:  <br/>
At the beginning of the journey, the user is presented with a scenario and given two possible actions to choose from. If the user fails to respond within the designated time, they are sent to the <b>inactivity loop</b>, effectively ending the interaction. For each choice the user makes, a corresponding <b>increment function</b> is triggered, keeping track of their score. Afterward, the user is directed to the next question, continuing the flow and further developing their path toward becoming either a Mage or a Warrior.
<img src="https://imgur.com/KPG0jjr" height="80%" width="80%" alt="RPG_Class_Chatbot"/>
<img src="https://imgur.com/HruRQ2J" height="80%" width="80%" alt="RPG_Class_Chatbot"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="RPG_Class_Chatbot"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="RPG_Class_Chatbot"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="RPG_Class_Chatbot"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="RPG_Class_Chatbot"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="RPG_Class_Chatbot"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
