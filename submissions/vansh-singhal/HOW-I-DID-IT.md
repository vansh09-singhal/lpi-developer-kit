How I Did It – Level 2

What I did, step by step
I cloned the project and opened it in VS Code. Then I ran npm install to install all dependencies, followed by npm run build to compile the project. After that, I executed npm run test-client to verify everything was working, and it ran successfully.

For the LLM setup, I installed Ollama and initially tried running a model, but faced issues. To avoid those problems, I switched to a lightweight model (TinyLlama), which ran smoothly. I tested it with a simple prompt to confirm it was working properly.

What problems I hit and how I solved them
The main issue I faced was while using Ollama. The model I initially tried didn’t run properly on my system, likely due to resource constraints. After identifying this, I switched to a smaller, lightweight model (TinyLlama), which resolved the issue and worked without any errors.

What I learned that I didn’t know before
This task helped me understand the complete project setup workflow—from installing dependencies to building and testing.