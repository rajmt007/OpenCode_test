# OpenCode_test

https://www.youtube.com/watch?v=ihElfZhR-eI


REA GitHub (free, MIT): https://github.com/morluto/rea
OpenCode: https://opencode.ai/download
DeepSeek Harness: https://deepseek.com/en/harness
OpenRouter (free models): https://openrouter.ai
NVIDIA free API keys: https://build.nvidia.com
Resource Library: https://maitis.ai/


How to use Claude Code for free
AI Tools
11-step guide, 3 tools
A complete setup and workflow guide. Install Claude Code, connect free AI models through FreeLLMAPI, build a 3D portfolio website, and try three more ways to use Claude Code for free.


Save
Copy link
Step-by-step guide
1
Before you start
You need a computer with internet access and a free Google account.
The install command in this guide is for macOS. Check the Claude Code site for Windows and Linux.
Free model limits change often, so some steps may look slightly different when you try them.
2
Tools you need
Website | Link | What it is used for

VS Code | https://code.visualstudio.com/ | Code editor where you open your project and run Claude Code.

Node.js | https://nodejs.org/ | Runs JavaScript on your computer. Install the LTS version.

Claude Code | https://code.claude.com/ | Anthropic's AI coding agent that works in your terminal.

FreeLLMAPI | https://github.com/search?q=FreeLLMAPI&type=repositories | Middleman that connects Claude Code to free AI providers. Open the official repository from the search.

Google AI Studio | https://aistudio.google.com/ | Where you create a free Gemini API key.

Ollama | https://ollama.com/ | Runs AI models locally on your own computer.

OpenRouter | https://openrouter.ai/ | One account and API key for many AI models, including free ones.

OmniRoute | https://github.com/marcpadz/omniroute | Gateway that connects several AI providers with fallback.

OmniRoute docs | https://omniroute.hagicode.com/ | Documentation for setting up OmniRoute.

3
Install Claude Code
Install the Node.js LTS version first, then install Claude Code.

For macOS

Open Terminal and run:

curl -fsSL https://claude.ai/install.sh | bash

Check the installation:

node --version
claude --version

Both commands should return version numbers.

4
Install FreeLLMAPI
FreeLLMAPI acts as a middleman between Claude Code and free AI providers.

Search for FreeLLMAPI on GitHub (https://github.com/search?q=FreeLLMAPI&type=repositories).
Open its official repository.
Go to the Releases section.
Download the installer for your operating system.
Install and open the application.
Check the repository for the latest installation instructions and supported platforms.

5
Connect Gemini API
Open Google AI Studio: https://aistudio.google.com/

Sign in with your Google account.
Open API Keys.
Click Create API Key.
Copy your API key and keep it safe.
Now open FreeLLMAPI:

Go to the Keys tab.
Click Add Key.
Select Google AI Studio.
Paste your API key.
Select the available Gemini models.
Save the configuration.
Check that the connection status shows Healthy.

Test your Gemini connection

Open the Playground tab and paste:

Hello! I am testing my free Gemini API connection.
Please introduce yourself briefly.

If Gemini replies, your API connection is working.

6
Connect Claude Code with FreeLLMAPI
Open FreeLLMAPI.
Go to the Agents tab.
Find Claude Code.
Copy the setup command shown there.
Open your terminal.
Paste and run the command.
This sets Claude Code to send its requests through FreeLLMAPI. Now open your project folder and run:

claude

Claude Code is ready to use with your chosen provider.

7
Build a 3D portfolio website
Create a project folder named:

3D Portfolio Website

Open the folder in VS Code and start Claude Code.

Copy-paste website prompt

Act as a professional full-stack developer
and creative UI/UX designer.

Build a premium dark-themed personal portfolio
website with impressive 3D animations.

Requirements:

Create a cinematic hero section.
Add an interactive 3D animation on the first screen.
Include an About Me section with statistics.
Create a Tech Arsenal section for skills.
Add a Selected Work section for projects.
Include a Let's Connect section with a contact form.
Use modern typography and dark aesthetics.
Add smooth scrolling and hover animations.
Make the website fully responsive.
Use clean and reusable components.
Use suitable technologies such as Three.js
or React Three Fiber if appropriate.

Create all necessary files, install dependencies,
run the website and fix any errors.

Make the final output visually impressive
and fully functional.

Run your website

Follow the commands Claude Code gives you. For a typical Vite project:

npm install
npm run dev

Open the local address it shows in your browser.

Fix errors with Claude Code

If you see an error, paste:

Inspect the project, identify the error,
fix the issue and run the website again.
Make sure the website works correctly.

8
Check your API usage
Open FreeLLMAPI and go to Analytics. Check:

Total requests
Token usage
Success rate
Models used
Estimated cost
This shows the actual usage and estimated cost of your website-building session.

9
Bonus: three more ways to use Claude Code for free
A. Ollama: run AI locally

Website: https://ollama.com/

Download and install Ollama.
Open its Models page.
Choose a model that suits your computer's hardware.
Download the model.
Connect Ollama to Claude Code using its official integration instructions.
Run a model with:

ollama run MODEL_NAME

Benefits: the model runs on your computer, uses no cloud API, and works offline once downloaded. Your computer's hardware decides how fast it runs.

B. OpenRouter: access many AI models

Website: https://openrouter.ai/

Create an account.
Open API Keys.
Create a new API key.
Visit the Models page.
Filter for free models.
Connect your API key to Claude Code using the supported setup.
Free models are subject to each provider's own limits.

C. OmniRoute: connect several providers

GitHub: https://github.com/marcpadz/omniroute

Install Node.js.
Install OmniRoute:
npm install -g omniroute

Start OmniRoute:
omniroute

Open the dashboard:
http://localhost:20128

Connect supported providers such as OpenRouter and NVIDIA.
Set up model routing and fallback order.
Connect Claude Code using the official integration instructions.
Documentation: https://omniroute.hagicode.com/

10
Final workflow summary
Install Node.js
Install Claude Code
Install FreeLLMAPI
Connect Gemini API
Connect Claude Code
Build the 3D portfolio website
Check API usage
Explore the three alternatives: Ollama, OpenRouter and OmniRoute
11
Warning
Free model access and limits can change at any time.
Free models may be slower or less capable than paid models.
Ollama's speed depends on your computer's hardware.
OpenRouter and other cloud providers have their own usage limits.
A zero-cost API estimate does not include hardware or other service costs.
Never share your API keys, passwords or private project files.
Check each provider's terms before you connect a third-party service.
That's it! You now have four ways to try Claude Code without starting on a paid Anthropic subscription.

Tools used
Ollama
OpenRouter
Claude
