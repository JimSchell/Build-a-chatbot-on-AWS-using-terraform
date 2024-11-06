# Build-a-chatbot-on-AWS-using-terraform
In this project I will be utilizing Amazon Lex and Lambda - this will be deployed using Terraform. I built a pizza chatbot which was able to adapt to various responses from customers



I created a pizza order chatbot using amazon Lex – this had to ability to order a variety of pizzas and drinks, I was able to set up multiple response and have a customised voice response, due to the versatility of Lex it was able to learn and adjust certain words not entered by the user for example, customer entered the word ‘beverage’ instead of ‘drink’ Lex was able to understand and give the correct response.
In this project I will be utilizing Amazon Lex and Lambda - this will be deployed using Terraform.


![image](https://github.com/user-attachments/assets/a737e494-a79d-4170-8989-cecea3361cc5)


Amazon Lex - is an AWS service for building conversational interfaces for applications using voice and text. With Amazon Lex, the same conversational engine that powers Amazon Alexa is now available to any developer, enabling you to build sophisticated, natural language chatbots into your new and existing applications
Lambda - runs your code on high availability compute infrastructure and performs all the administration of your compute resources. This includes server and operating system maintenance, capacity provisioning and automatic scaling, code and security patch deployment, and code monitoring and logging.


My first step in creating this project is to set up the base code in terraform and create the chatbot – at this stage I simply create the chatbot and given it a name “OrderPizza” this is created in my closest region – eu-west-2. Once the code is applied it has successfully created the bot in the AWS console.



![image](https://github.com/user-attachments/assets/caaa6fbf-de76-4b85-a3c5-3fc57ef19b29)

![image](https://github.com/user-attachments/assets/e6f684a5-f24f-4a36-8688-367c626be42e)


