# Own-Chat-GPT
This Project was done in Replit Platform with the help of Open AI API Service.
Certainly! Here's a step-by-step breakdown of the provided code for creating a ChatGPT model on the Replit platform using the OpenAI API service:

1. Create OpenAI Account:

    Sign up for an account on the OpenAI platform using your mobile number and email address.

2. Obtain API Key:

    After logging in to OpenAI, go to your profile settings and access API keys.
    Create a new secret key and copy it for later use.

3. Create Replit Account and Repl:

   Create an account on the Replit platform.
   Start by creating a new Repl with a suitable title, choosing the "Python" language.


4. Add API Key to Replit Secrets:

   In your created Repl, navigate to the "Tools" section and open the "Secrets" tab.
   Create a new secret with the key as "OPENAI_API_KEY" and the value as the copied API key from OpenAI.


5. Code Explanation:

   Import openai:
   
    Imports the OpenAI module, which provides an interface for interacting with OpenAI's language models and other AI services.
   
   Import os:

    Imports the os module, which provides a way to interact with the operating system and environment variables.

   
   This code sets the api_key attribute of the openai module to the value of an environment variable called OPENAI_API_KEY. The os module provides a way to access                environment variables in Python. The api_key is used to authenticate requests to the OpenAI API, which is a service that provides access to machine learning models for       natural language processing (NLP) and other tasks. By setting the api_key, this code allows the Python program to use the OpenAI API to perform NLP tasks.
   The code starts by prompting the user for their initial question or instruction.
    Inside a loop, it sets up the OpenAI API key from the Replit secrets.
    It uses the OpenAI API to generate a response from the assistant based on the user's input.
   The API call includes two messages, one from the "system" role and one from the "user" role.
   The "system" message is a greeting that sets the tone for the chatbot's response.
   The "user" message is a prompt that asks the chatbot
    The assistant's reply is extracted and printed.
    The loop continues, asking the user for another question or instruction.
7. Running the Code:

     Run the code in your Repl on Replit.
     You can interact with the ChatGPT model by entering questions or instructions, and the assistant will respond accordingly.
By following these steps, you've created a functional ChatGPT model using the OpenAI API service on the Replit platform.

Regarding the API issue, many users may encounter an error if they do not have sufficient credits to access the OpenAI API keys.
If you are facing this problem, it is crucial to verify the usage of your API key, particularly if it has a balance of $0 or if it has expired.
In such cases, it is recommended to create a new account using a different phone number and a different email ID.
By doing so, you will receive $5 worth of credits, which will remain valid for three months. 
