# CoffeeShop_Chatbot
This is the code to create a simple chatbot using Deep Learning Algorithms.

The chatbot is designed to react to questions on ordering coffee and making a table reservation at a coffee shop. Just a few of the numerous "intents" or types of inquiries that are covered are greetings, ordering coffee, coffee variations, coffee sizes, coffee additives, coffee costs, specialty beverages, booking a table, location, and operation hours. For each goal, a list of potential user inputs (patterns) is provided, along with the chatbot's pertinent responses. For instance, if a user asks, "Can I order a coffee?the chatbot will understand the intent "order_coffee"and reply, "Of course, what size would you like your coffee?”.

| Intent | Expected Patterns | Expexted Responses |
|--------|-------------------|--------------------|
| greeting | [Hi, Hello, Hey there, Good morning] | ['Hello! How can I help you today?', 'Hi! What can I do for you?', 'Hey there! How can I assist you?']|
| order_coffee | [Can I order a coffee?, I want a coffee, Can you make me a coffee?, Coffee please] | ['Sure, what type of coffee would you like?', 'Of course, what size would you like your coffee?', 'Certainly, would you like anything else with your coffee?'] | 
| coffee_types | [What types of coffee do you have?, What are your special types of coffee?] | ['We have espresso, cappuccino, latte, and more with any combinations!', 'We have a few specials today, pumpkin spice latte and our peppermint mocha.'] |
| coffee_size | [What sizes do you have?, How big are your coffee cups?] | ['We have small, medium, and large cups.', 'We have small, medium, and large sizes of cups.', 'Our small size is 8 oz, our medium size is 12 oz, and our large size is 16 oz.'] | 
| smallCoffee_price | [How much does a small coffee cost?, What is the price a small size coffee?, How much is small a coffee for?] | ['Our small coffee is $2.90.', 'The price of our small coffee is $2.90.', 'Our small coffee is $2.90.'] | 
| mediumCoffee_price | [How much does a medium coffee cost?, What is the price a medium size coffee?, How much is medium a coffee for?] | ['Our medium coffee is $3.50.', 'The price of our medium coffee is $3.50.', 'Our medium coffee is $3.50.'] |
| largeCoffee_price | [How much does a large coffee cost?, What is the price a large size coffee?, How much is large a coffee for?] | ['Our large coffee is $2.90.', 'The price of our large coffee is $2.90.', 'Our large coffee is $2.90.'] | 
| menu_options | [Can you show me the menu?, What's on the menu?] | ['We have a variety of options including hot beverages, cold beverages, salads, and snack options!'] | 
| location | [Where are you located?, What is your address?, Can you tell me where you located?] | ['We are located at 33 Yonge Street', 'Our address is 33 Yonge Street.', 'You can find us at 33 Yonge Street.'] | 
| hours_of_operation | [When are you open?, What are your hours?, What days are you open?] | ['We are open from 9am to 10pm, Monday to Saturday, and from 10am to 8pm on Sundays.', 'Our store hours are 7am to 9pm Monday through Friday, and 9am to 7pm on weekends.'] | 
| payment_methods | [How can I pay?, What are the payment methods?, Can I use Apple Pay?] | ['We accept cash, credit cards, and mobile payments such as Apple Pay and Google Wallet. your order will be ready soon', 'You can pay with cash or any major credit card, including Visa, Mastercard, and American Express, your order will be ready soon', 'Yes, Make the payment and wait for the order, your order will be ready soon'] | 
| membership | [Do you have a membership program?, How does your membership program work?, Can you tell me about your rewards program?] | ['Yes, we have a loyalty program! You earn points for every purchase you make, which can be redeemed for discounts on future purchases.', 'Our loyalty program is simple: you earn points for every purchase, and can redeem those points for discounts on future orders. The more you shop, the more you save!', 'Our rewards program is a great way to save money on your favorite products. You earn points for every purchase, and can redeem those points for discounts on future orders.']| 
| complaints | [I have a complaint I'd like to file!, I'm not happy with my order, I need to report an issue] | ["I'm sorry to hear that. Please let me know what the issue is so we can address it and make things right.", 'I apologize for any inconvenience. Please speak to a manager and we will do our best to resolve the issue.', 'Thank you for bringing this to our attention. Please speak to my manager. We take all complaints seriously and will investigate the issue.'] | 
| thank_you | [Thank you, Thanks, Appreciate it] | ["You're welcome! Have a great day!", 'No problem, happy to help!', 'Glad I could assist you. Enjoy your meal!']|


<img width="468" alt="image" src="https://user-images.githubusercontent.com/90365773/233862512-b8f49270-4b93-420b-9e0a-13e63a78e364.png">


<img width="468" alt="image" src="https://user-images.githubusercontent.com/90365773/233862533-c0dbeebd-a193-4ca0-9371-c497fea884ed.png">
Here are the last two epochs, the model is train to about 65.85%.
However, the model is seeming to be over fitting due to less data available. This might be because the model doesn’t really need 1000 epochs.
<img width="468" alt="image" src="https://user-images.githubusercontent.com/90365773/233862539-7b0b1c29-7f68-4e46-9572-3b5b5f668513.png">


By adding more intents, patterns, and responses, the bot's knowledge base will grow. The chatbot will be able to answer to user enquiries more efficiently and precisely as a result. 
Improve natural language processing (NLP): The effectiveness of a chatbot hinges on its ability to decipher and comprehend natural language. As part of NLP, the bot's ability to recognise and understand linguistic subtleties, synonyms, and patterns must be enhanced. 
machine learning included: By learning from user interactions, machine learning can help the chatbot develop its responses over time. This could mean utilising unsupervised learning to identify patterns and trends in user questions or using prior interactions to teach the bot. 
Utilize contextual data: By taking context into account, the chatbot can react more precisely and personally.


 


