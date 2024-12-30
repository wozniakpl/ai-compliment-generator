# AI Compliment Generator

A simple web app for generating AI-powered compliments using [Xenova/distilgpt2](https://huggingface.co/Xenova/distilgpt2). The purpose of this project is to demonstrate running a lightweight language model (LLM) directly in the browser, intended mostly for fun and casual use.

## How It Works
1. **Lightweight Model**:
   - The app uses the `distilgpt2` model, a smaller and more efficient version of GPT-2, making it suitable for in-browser execution without heavy resource requirements.

2. **Model Loading in the Browser**:
   - The app leverages the [Hugging Face Transformers](https://huggingface.co/docs/transformers/index) library to load and execute the model entirely within the browser using WebAssembly (WASM) and JavaScript.

3. **Prompt-Based Text Generation**:
   - Users select a starting prompt from a dropdown menu.
   - Clicking the "Get a Compliment" button generates a continuation of the prompt using the locally loaded model.

4. **No Server Dependency**:
   - All computations happen locally in the user's browser, ensuring privacy and requiring no backend server.

## License
Licensed under the Apache License 2.0. The AI model is provided by Xenova on Hugging Face.
