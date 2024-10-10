# Support-Chatbot-Representation

This project, which was prepared with the aim of being a classic chatbot-support chatbot found on websites, is a chatbot trained and matched with neural network to answer frequently asked questions and general technical service-warranty related problems. Chatbot, which we trained by matching multiple answers to approximately 460 topics, gives output as in the sample images below. We first published the sample application in the local browser and then as a web app as heroku-app and tested it.

![Bot1](https://github.com/user-attachments/assets/efba9ae1-2436-4934-913c-0a724a7f105d)
![bot3](https://github.com/user-attachments/assets/6b82d754-2611-4766-922b-8f90212bc088)

We also made a condition call to see the accuracy rates of the answers to be given to the user with the edits we made on the chat.py page where we run the application in the console. If there is a match in the question-answer database for what the user is asking and this answer is higher than 0.75 probability, we give the user a direct answer, but if not, we can suggest the 5 options with the highest probability as if they were the title the user meant.

![bot2](https://github.com/user-attachments/assets/6892456d-3ec3-4144-afcb-f54264f7409b)
![bot4](https://github.com/user-attachments/assets/ba05bd6b-1912-4238-9d9a-528793348f82)
![bot5](https://github.com/user-attachments/assets/1f60a83e-4e22-4067-9f5b-f3e52edd3130)
