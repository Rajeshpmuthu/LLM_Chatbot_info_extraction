# LLM_Chatbot_info_extraction
Aim to create an engaging, persuasive, and user-friendly conversational experience. Our goal is to encourage users to willingly share their information, recognizing that initial responses may not always be accurate.
Develop a conversational interface similar to the one demonstrated by Formless AI.
Implement multiple chat agents, each with a specific role (e.g., "convincing to give details",
"Extract and Verify user information," "Format the extracted information").
2. The bot should Initiate the conversation.
3. Design a coherent conversation flow where users will easily give the information or convince
well to give their info.
● If the user is hesitant then initiate small talk and later circle back to the question
regarding their personal information.
4. Details to extract: Name, email, phone no, Address, Date of birth, Education.
5. Make sure the Chat flow is consistent or natural and minimum hallucinations (No question
repetitions, out of context question) shouldn’t happen.
6. You can use any Large language model of your choice for agents, also your choice of
parameter for tuning the agent/prompt.
7. Ensure the conversation logic guides users through the agent’s questions seamlessly.
8. After gathering user details from agents, format the data appropriately.
● You should save the user details as they are obtained and not wait till all the details are
received.
9. Create a CSV file using libraries like pandas in Python.
