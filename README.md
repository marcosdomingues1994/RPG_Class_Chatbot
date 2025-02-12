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
<h3>Launch the utility:</h3> <br/>
In this flow, a user identification node is used to personalize the experience, ensuring that the chatbot recognizes and tailors the interaction to the user’s responses. Following this, a question node is introduced to verify if the user is ready to proceed with the adventure. If the user does not respond within a designated time (timeout), they are automatically redirected to the finish node, gracefully ending the interaction.
<img src="https://i.imgur.com/YrzNf8r.png" height="80%" width="80%" alt="RPG_Class_Chatbot"/>
<br />
<br />
<h3>Jorney starts, first interaction:</h3>  <br/>
At the beginning of the journey, the user is presented with a scenario and given two possible actions to choose from. If the user fails to respond within the designated time, they are sent to the <b>inactivity loop</b>, effectively ending the interaction. For each choice the user makes, a corresponding <b>increment function</b> is triggered, keeping track of their score. Afterward, the user is directed to the next question, continuing the flow and further developing their path toward becoming either a Mage or a Warrior. <br/>
<img src="https://i.imgur.com/AQgU5z9.png" height="80%" width="80%" alt="RPG_Class_Chatbot"/>
<img src="https://i.imgur.com/BRWbh45.png" height="80%" width="80%" alt="RPG_Class_Chatbot"/>
<br />
<br />
<h3>General overview:</h3> <br/>
This section showcases the full branching logic of the user's choices. After question 3, the user's score in one of the classes may become high enough that the subsequent choice becomes irrelevant. In this case, the chatbot will display a message like:<br/>
"Humm, parece que você já tem um caminho claro para trilhar. Mas antes de revelarmos seu destino, vamos para a última pergunta!"<br/>
<img src="https://i.imgur.com/o45taG0.png" height="80%" width="80%" alt="RPG_Class_Chatbot"/>
<img src="https://i.imgur.com/mYplMJT.png" height="80%" width="80%" alt="RPG_Class_Chatbot"/>
<br />
<br />
<h3>Class enlightment:</h3>  <br/>
Following question 4, the user is directed to their class enlightenment screen, where a brief text outlines their class's abilities and strengths. A picture representing the class persona is also displayed, alongside the finish component to conclude the interaction.
<img src="https://i.imgur.com/1vunyjL.png" height="80%" width="80%" alt="RPG_Class_Chatbot"/>
<br />
<br />
<h3>Tiebreaker:</h3>  <br/>
In the event of a tie after question 4, the user will be directed to a 5th question to help break the tie. After this, the user is sent to the finish loop, where the journey ends.
<img src="https://i.imgur.com/Lhtl9St.png" height="80%" width="80%" alt="RPG_Class_Chatbot"/>
<br />
<br />
<h3>User Jorney Simulation:</h3>
<img src="https://i.imgur.com/4KoCffo.png" height="30%" width="30%" alt="RPG_Class_Chatbot"/>
<img src="https://i.imgur.com/8NGz2eg.png" height="40%" width="40%" alt="RPG_Class_Chatbot"/>
<img src="https://i.imgur.com/Mum6eJV.png" height="80%" width="80%" alt="RPG_Class_Chatbot"/>
<img src="https://i.imgur.com/OQBwxdp.png" height="80%" width="80%" alt="RPG_Class_Chatbot"/>
<img src="https://i.imgur.com/bCDp9HK.png" height="80%" width="80%" alt="RPG_Class_Chatbot"/>
<img src="https://i.imgur.com/uhujxpt.png" height="80%" width="80%" alt="RPG_Class_Chatbot"/>
<img src="https://i.imgur.com/GINWZyk.png" height="80%" width="80%" alt="RPG_Class_Chatbot"/>
<img src="https://i.imgur.com/utMr43C.png" height="80%" width="80%" alt="RPG_Class_Chatbot"/>
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
