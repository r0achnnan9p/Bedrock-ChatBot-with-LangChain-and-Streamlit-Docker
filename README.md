# Bedrock ChatBot with LangChain and Streamlit 💬 
A simple and clear example for implement a chatbot with Bedrock(Claude) + LangChain + Streamlit. Just `cd` to the corresponding folder and run the code:
```
streamlit run bedrock_chatbot.py
```

The bot is equipped with chat history using [ConversationBufferWindowMemory](https://python.langchain.com/docs/modules/memory/types/buffer_window) and [StreamlitChatMessageHistory](https://python.langchain.com/docs/integrations/memory/streamlit_chat_message_history), and provided with both simple(batch) and streaming modes. Demo shown as below:

https://github.com/davidshtian/Bedrock-ChatBot-with-LangChain-and-Streamlit/assets/14228056/9bbcf241-134e-4b8b-8080-a9000029997b

Streaming mode demo shown as below:

https://github.com/davidshtian/Bedrock-ChatBot-with-LangChain-and-Streamlit/assets/14228056/cdff3813-fbfc-4b2f-83bc-b4016c921265



## Configuration AWS credentials

- Copy the `.env_aws.example` file to a new file named `.env_aws`.
- Replace the placeholder values in `.env_aws` with your actual AWS credentials.
- Note: Do not commit the `.env_aws` file to the repository. It is included in the `.gitignore` file to prevent sensitive information from being exposed.

## Run
docker compose up