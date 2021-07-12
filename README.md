# ChatBot_using_IBM_WatsomAssistant
Through this project, a new tool that is used in AI applications will be introduced and used to create a Chatbot. The tool is Watson Assistant, which was invented by IBM. Watson Assistant was created to improve customer’s experiences and to provide them fast, consistent and accurate answers, which in return make customers happy. What makes Watson Assistant special is its ability to continuously learn from customer conversations. So, the task of this week is to create a Chatbot using IBM Watson, the Chabot assistant that will be created called “UPMer” and she works for UPM’s website visitors, students or staff.

# How to use Watson Assistant 
To begin with Watson Assistant, there are two main sections to deal with, the Assistant and the Skills. The two sections will be introduced below.

The Assistant is the “Chatbot” that talks to the customers and help them. While Skills is where the chatbot developer can create a skill and train the chatbot to master that skill. For instance, our chatbot UPMer “Assistant” is linked with Orientation “skills” which was created such that she helps students or visitors with finding academic information about colleges and departments, or tell them if the admission is open and what are the required documents and how to apply. Not only that but also she is smart enough to understand visitor’s needs and know if it is morning, afternoon or evening time! However, she needs more data and more training to get smarter. In order to create a skill there are three important concepts to deal with, intents, entities and dialog. 

**1) #Intents**
Intent is the user’s intention or purpose of talking to the chatbot or simply the assistant. For example, a user says “Hi” to the assistant, and the assistant understands the word “Hi” as “greeting intent”. To make the assistant able to understand different words and ways of greetings, it is better to provide her with as many examples as we can. The figure below shows how a greeting intent is created with 16 different examples.
![intent1](https://user-images.githubusercontent.com/85955049/125173650-ec5a9400-e1c8-11eb-8c16-044f68f4fef1.png)


The table below lists all intents that were created under the orientation skill.
![intents table](https://user-images.githubusercontent.com/85955049/125173744-74d93480-e1c9-11eb-9858-2ae59a94adf5.png)

Note: Intents are labeled with (#). 

**2) @Entities**
Entities are the more detailed parts of the user intents. For instance, the user might “order a pizza” which is the intent, but the “type of pizza” he wants to order is the entity. In our example, the intent might be knowing more about “college of engineering”, however knowing about an “engineering department”, such as the electrical engineering department, is the entity. The figure below shows the list of entities added to the orientation skill. 
![entities1](https://user-images.githubusercontent.com/85955049/125173844-0a74c400-e1ca-11eb-993b-69ec398e6b7c.png)
Note: Entities are labeled with (@).

**3) Dialog**
The figure below illustrates the dialog of the orientation skill, where the flow of the conversation is defined. For instance, the node “College of Engineering” is set to recognize the user’s intent of asking about college of engineering. While the child node “Engineering Departments” is set to recognize user’s entity of asking about a department under college of engineering. If the user asked to know about the college of engineering in general, the assistant will send a link to the user while it will ask the user which engineering she/he wants to know about and then send the link of the department’s web page.
![dialog1](https://user-images.githubusercontent.com/85955049/125173918-9a1a7280-e1ca-11eb-9aa1-f1cb50a89963.png)

There are many other features that can be applied to the chatbot such as transferring the visitor to a human agent or making reservations and many other features. However, it takes weeks and months for creating and training a fast, accurate, consistent and smart chatbot that is capable of covering the company’s customer service plan.  

# ChatBot Training 
Since the website visitors have different minds, different ways of speaking and different needs, it is recommended to train the assistant continuously and by different couches to create a smart, fast and accurate chatbot assistant! The first figure below shows a training process for “application requirements” with an intent of asking about “Admission and Registration” and entity of “Application”. The chatbot did not understand the intent of the user at the first time, then the intent was chosen from the list to train the chatbot. While the second figure shows the response of the assistant after repeating the same question, and the response is correct! This proves how Watson assistant can learn fast and smart. 

![chat11](https://user-images.githubusercontent.com/85955049/125174043-40667800-e1cb-11eb-997c-aef1cefd3379.png)
![chat12](https://user-images.githubusercontent.com/85955049/125174048-4b210d00-e1cb-11eb-9d81-9d6efacf4561.png)

# Successful Chats
Two examples of successful chats between the assistant and the user are shown below.

**Chat 1:**

![EC11](https://user-images.githubusercontent.com/85955049/125174141-e31ef680-e1cb-11eb-9486-5d1a53d0ba89.png)

![EC12](https://user-images.githubusercontent.com/85955049/125174153-ee722200-e1cb-11eb-82db-694470ddafcd.png)

![EC13](https://user-images.githubusercontent.com/85955049/125174157-f762f380-e1cb-11eb-9e79-088493f28c6e.png)


**Chat 2:**

![EC21](https://user-images.githubusercontent.com/85955049/125174166-06e23c80-e1cc-11eb-9357-e9114cb29586.png)

![EC22](https://user-images.githubusercontent.com/85955049/125174171-15305880-e1cc-11eb-965f-ea9a23610921.png)

![EC23](https://user-images.githubusercontent.com/85955049/125174176-1feaed80-e1cc-11eb-8091-1725e9c8059d.png)

# How to Style and Integrate the ChatBot

The figure below shows how the assistant looks like on the website. Some features such as the background color, or the heading text and the picture of the assistant are editable.
![style](https://user-images.githubusercontent.com/85955049/125174232-71937800-e1cc-11eb-9196-d39ad573cc38.png)

In order to embed the chatbot assistant on the website, the script shown in the figure should be added to the body of the index.html file of the website.
![embed](https://user-images.githubusercontent.com/85955049/125174241-8ff97380-e1cc-11eb-80ae-ccb38d27cbdb.png)


