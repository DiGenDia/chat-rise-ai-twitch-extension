# DiGenDia Chat Rise AI - Twitch Extension

## Before starting

This is a demo application We want to create to verrify our Idea of having a defined workflow of prompts for code implementation. we start with some base information like requirements and architecture of the overall project, we write some user stories, verrify them, cut them into dev stories and into tasks, which can be implemented based on the base information as a surounding context.
This is **NOT** our idea at all, we saw the YouTube Video [Unlock AI Coding with Workflow-Driven, Tuned Prompt Chains](https://www.youtube.com/watch?v=t-i2x3APvGQ) of **Coding the future with AI** and used the prompts from their [Github repository](https://github.com/codingthefuturewithai/software-dev-prompt-library) to have an easier start.

## This Project

**Chat Rise AI** empowers streamers to elevate their Twitch chat experience with cutting-edge AI integration. This extension enables seamless interaction between streamers and their communities by leveraging customizable AI commands, templates, and the flexibility to connect with the Large Language Models (LLMs) of your choice.

Whether you're looking to foster engagement, spark creativity, or introduce unique AI-driven features, **Chat Rise AI** makes it simple to transform your chat into an interactive and dynamic space.

Rise above the ordinary. Empower your chat with AI.

## Start with Aider on Gemini

**Disclaimer:**
You can use what ever agent and model you like to. The existing code is tested and verrified by using [Aider](https://aider.chat/) and the Gemini Model `gemini/gemini-1.5-flash-latest`

Create `.env` file from dist

```bash
cp .env.dist .env
```
which is out of the repository. Create your API Key at [Google AI Studio](https://aistudio.google.com/app/apikey?hl=de) and add it to the `.env` file as the value of `GEMINI_API_KEY=...`. Now you can start aider

```bash
aider --model gemini/gemini-1.5-flash-latest
```

Use prompt

```bash
# To not get any file changes 
/chat-mode ask

# An example prompt to generate requirements - follow steps
/read-only prompts/requirements/assistant-specific/aider/initial-project-requirements-management-prompt.md

# Trigger Start
\#generate-requirements
```
