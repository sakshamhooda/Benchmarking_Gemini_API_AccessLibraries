# Benchmarking_Gemini_API_AccessLibraries

Here in the notebook (https://colab.research.google.com/drive/1YiVKV5jZsZBKPUFV7S-3wUVVCt999UDH?usp=sharing) I intend to compare perfomance metrics when Google Gemini-API is called using newly launched OpenAI libray method as well as conventional Gemini-API.

https://developers.googleblog.com/en/gemini-is-now-accessible-from-the-openai-library/

This benchmark suite measures several key performance metrics:

1. Latency:

    - Response time for each API call
    - Standard deviation to measure consistency
    - Includes network transfer time


2. Memory Usage:

  - Memory consumption per request
  - Peak memory usage
  - Memory cleanup efficiency


2. Additional Features:

  - Multiple test prompts of varying complexity
  - Error handling and retry logic
  - Visualization of results
  - Statistical analysis of performance metrics



The benchmark uses 5 different types of prompts to test various aspects of the API:

- Short factual responses
- Code generation
- Literary analysis
- Scientific explanation
- Technical concepts

