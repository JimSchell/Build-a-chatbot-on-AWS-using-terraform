# Build-a-chatbot-on-AWS-using-terraform and the AWS console
In this project I will be utilizing Amazon Lex - this will be deployed using Terraform and the AWS console. I built a pizza chatbot which was able to adapt to various responses from customers



I created a pizza order chatbot using amazon Lex – this had to ability to order a variety of pizzas and drinks, I was able to set up multiple response and have a customised voice response, due to the versatility of Lex it was able to learn and adjust certain words not entered by the user for example, customer entered the word ‘beverage’ instead of ‘drink’ Lex was able to understand and give the correct response.
In this project I will be utilizing Amazon Lex and Lambda - this will be deployed using Terraform.


![image](https://github.com/user-attachments/assets/121c58d3-900b-4cad-b6e8-d32155ce9f16)



Amazon Lex - is an AWS service for building conversational interfaces for applications using voice and text. With Amazon Lex, the same conversational engine that powers Amazon Alexa is now available to any developer, enabling you to build sophisticated, natural language chatbots into your new and existing applications
Lambda - runs your code on high availability compute infrastructure and performs all the administration of your compute resources. This includes server and operating system maintenance, capacity provisioning and automatic scaling, code and security patch deployment, and code monitoring and logging.


My first step in creating this project is to set up the base code in terraform and create the chatbot – at this stage I simply create the chatbot and given it a name “OrderPizza” this is created in my closest region – eu-west-2. Once the code is applied it has successfully created the bot in the AWS console.



![image](https://github.com/user-attachments/assets/caaa6fbf-de76-4b85-a3c5-3fc57ef19b29)

![image](https://github.com/user-attachments/assets/e6f684a5-f24f-4a36-8688-367c626be42e)


The latest version of amazon lex v2, is built and designed to be utilised on the console as the first port of call, you can use IAC tools such as terraform and cloudformation but you still need to incorporate the use of the console.

Using the console first step is to create an intent, this step is the first interaction between the customer and the chatbot, the locale used for the chatbot was EN-US and voice used was preselected as Danielle, I inputted a couple of typical phrases ‘Hi’ and ‘Hello’ what is really clever with Lex the ML in the background can pick up other greetings such as ‘Yo’, a couple of responses were fitted as seen. 


![image](https://github.com/user-attachments/assets/15b7eb5d-5ff3-42d5-a89c-858a2e508d92)




Next stage was to create utterances, So this part is user input, so a customer wanting to order a pizza, with a specific topping, So I needed to create the next stage in the dialogue which is ‘I would like to order pizza’ with a response to this, followed by slot types, this gathered more information such as, size of pizza and toppings available. 

![image](https://github.com/user-attachments/assets/544dddc7-ee9d-4108-a159-6c2bb0d65173)



Next in the order process I needed to create the confirmation – if the customer successfully orders the pizza we create it and it the customer changes their mind we can also get the chatbot to respond correctly to this.


![image](https://github.com/user-attachments/assets/599c68e7-428a-4541-92ce-ae088efa91e2)



![image](https://github.com/user-attachments/assets/4052e946-c2de-4ba4-980c-d5d9e084f1a6)

So now I have the slots in place and utterance a basic version of a fully working chat bot has been deployed. 

![image](https://github.com/user-attachments/assets/3ba56800-73c8-4e25-9ff2-ac850289b25a)![image](https://github.com/user-attachments/assets/6e50e2ff-1413-4ab8-bd64-8cede0699324)






































