# build-custom-chat-gpt
Create and switch to a virtual environment before installing dependencies for openai and other libraries. 

python -m venv venv 
venv\Scripts\activate     # for windows 

Install the OpenAI Python library using pip. 

     pip install openai 

Gradio based frontend creation 

Gradio is an open-source Python library used to build AI related web applications. It allows developers to create user-friendly and customizable interfaces. 

Follow the below steps to create gradio based frontend for displaying the content. 

Install the gradio python library using pip. 

pip install gradio 

Run the app using the following command, 

python chatgpt_demo.py 

Create the environment 

Create and switch to a virtual environment before installing dependencies for openai and other libraries. 

python -m venv venv 
source venv/bin/activate  # for linux 
venv\Scripts\activate     # for windows 

1.3 Install dependencies 

Install the openai, fastapi, uvicorn, itsdangerous and python-dotenv libraries using pip. 

pip install openai fastapi uvicorn itsdangerous python-dotenv 

 

Run backend server 

Run the backend python server using the following command. 

python app.py 

 

You can hit the url http://127.0.0.1:3000 once the server is up and running. 

Create the frontend app 

Create a react application using create-react-app cli. 

npx create-react-app chatbot-frontend 

Run the app 

run the backend server. 

Run the frontend react app using the following command. 

npm start 

 

 

Video link: 

https://1drv.ms/v/c/c40e55a2501fc067/ESZcsG_EJUhOuxLrQ8IjACkBMge_ObZhDyB7TKwXB5TjaQ?e=4I8NtZ 
