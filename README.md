# AI Chatbot with TTS and STT

Useing this as an example project from Coursera

Note the docker build will fail because it is attempting to copy a certificate which you must have from the Coursera IBM SkillsLab

Module 3 of Building Generative AI-Powered Applications with Python

## Running 

docker build . -t voice-chatapp-powered-by-openai
docker run -p 8000:8000 voice-chatapp-powered-by-openai

It also may fail because there is an API key needed for openai