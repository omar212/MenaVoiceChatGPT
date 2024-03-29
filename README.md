# ChatGPT AI Voice Chatbot 
## ( I call it Mena Voice Chat GPT, because my fiancé knows everything 😂 )

<p align="center">
  <img width="416" alt="MenaVoiceChatGPT" src="https://user-images.githubusercontent.com/34172611/237021444-9d5ef620-3f69-4c4c-9deb-f6f0338de60a.png">
</p>


This is a web-based AI voice chatbot built using React, TypeScript, and Tailwind CSS. The chatbot is powered by the FastAPI combo and the OpenAI GPT-3 language model provided by OpenAI. The project utilizes the Elevenlabs API for voice input and output.

## Features

- Voice chatbot interface using Elevenlabs API for voice input/output
- AI-powered chatbot using OpenAI's GPT-3 language model
- Responsive UI design using Tailwind CSS
- Real-time response and feedback using FastAPI combo
- Built using React and TypeScript


## Usage

To use the chatbot, simply visit the web page and click on the microphone button to start speaking with the AI chatbot. The chatbot will respond in real-time using voice output and the conversation will be displayed on the screen.

Sure, here's an updated version of Step 2 of the installation instructions that includes the additional step of opening two terminals:

## Installation

1. Clone the repository to your local machine.

2. Install the dependencies using `npm install` for the frontend.

3. Get your OpenAI API key and OpenAI org key:
   - Go to the [OpenAI website](https://openai.com/) and create an account if you haven't already.
   - After logging in, navigate to the [API page](https://beta.openai.com/docs/api/overview) and click on the "Create new API key" button.
   - Follow the prompts to create a new API key.
   - Make sure to copy the API key and org key and keep them in a safe place.

4. Get your Eleven Labs API key:
   - Go to the [[Eleven Labs website](https://eleven-labs.com/en/)](https://elevenlabs.io/) and create a free account if you haven't already. 
   - After logging in, navigate to the bottom left corner of the screen where your profile picture is and click your image and look for "Profile + API Key"
   - Make sure to copy the API key and keep it in a safe place.

5. Add the API keys to the `.env` file:
   - Create a new file named `.env` in the root directory of your project.
   - Copy the contents of the `.env.template` file into the `.env` file.
   - Replace the values of the `OPENAI_API_KEY`, `OPENAI_ORG_KEY`, and `ELEVENLABS_API_KEY` environment variables with your respective API keys.

6. Make sure to add a credit card to your OpenAI login:
   - OpenAI provides a free trial of their GPT-3 API, but you need to add a credit card to your account to use the API beyond the trial period. This is to prevent abuse of the API and ensure fair usage.
   - Go to the [Billing page](https://beta.openai.com/billing) on the OpenAI website and follow the instructions to add a credit card to your account.

7. Open two terminals, one for the frontend and one for the backend:
   # Backend
   - In the first terminal, navigate to the root directory of the project and run the command `source venv/bin/activate` to activate the virtual environment.
   - Next, run the command `uvicorn main:app --reload` to start the backend server.
   # Frontend
   - In the second terminal, navigate to the root directory of the project and run the command `yarn dev` to start the frontend development server.

Now you should be able to use the ChatGPT AI Voice Chatbot on your local machine with the provided API keys.

That's it! You can now access the chatbot on your local machine.

## Contributors

- [Omar Elnagdy](https://github.com/omar212)

Feel free to contribute to this project by submitting a pull request.
