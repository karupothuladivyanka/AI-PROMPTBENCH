# AI-PROMPTBENCH
AI-PROMPTBENCH is a React-based web application designed to compare responses from multiple large language models (LLMs) like OpenAI GPT-4, Anthropic Claude, and Ollama Gemma 2 in real-time. It allows users to send a single prompt to all models simultaneously and analyze differences in their responses.

# Features

. Multi-Model Comparison: Send a prompt to OpenAI GPT-4, Claude, and Gemma 2 at the same time.

. Response Tracking: Displays responses in real-time and highlights which model responded the fastest.

. Dynamic UI: Each model’s response is color-coded with loading indicators and response badges.

. Asynchronous Handling: Independent API calls ensure fast and reliable response fetching.

. Interactive Analytics: Keeps track of the order of model responses to help users analyze speed and output differences.

# UI Overview

. The UI is designed for clarity and interactivity:

. Shared Prompt Area: A single text area to enter prompts that will be sent to all models.

. Submit Button: Sends the prompt to all models simultaneously and displays a loading state while responses are fetched.

. Response Order Section: Displays an ordered list of models based on the speed of their responses. The fastest model is highlighted.

. Model Boxes: Each model has its own panel with color-coded borders and titles, showing the response content and a badge indicating response order.

. Dynamic Feedback: Loading indicators, response badges, and real-time updates make it easy to compare outputs at a glance.


![App Output](https://github.com/karupothuladivyanka/AI-PROMPTBENCH/blob/main/Screenshot%202025-11-20%20133228.png?raw=true)

# Installation

1. Install Dependencies

   .npm install

This will install all the required packages for the project.

2. Start the Development Server

   .npm start

The app will start on http://localhost:3000 (default React port).

Make sure your backend API (LLM endpoints) is running at http://localhost:8085 as expected.

3. Open in Browser

  Go to http://localhost:3000 to access the app.

  Enter a prompt and click “Compare All Models” to see responses.

# Usage

. Enter your prompt in the text area.

. Click “Compare All Models” to send the prompt to all LLMs.

. View responses as they arrive and see which model responds fastest.

. Analyze differences in responses for insights and evaluation.

# Tech Stack

. Frontend: React, JavaScript, CSS

. State Management: React Hooks (useState, useCallback)

. API Handling: Fetch API for asynchronous requests to local LLM endpoints

. Styling: Custom CSS for model highlighting and dynamic UI

# Future Improvements

. Add support for more LLMs and model versions.

. Implement response caching to speed up repeated prompts.

. Include export options to save responses for offline analysis.

. Enhance UI/UX with charts or metrics for model comparison.
