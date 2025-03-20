# ChatGPT Prompt Engineering for Developers

## Course Overview
This course, led by Isa Fulford (OpenAI) and Andrew Ng (DeepLearning.AI), provides best practices for using Large Language Models (LLMs) to build AI-powered applications efficiently. It includes hands-on practice with the OpenAI API and covers key applications such as summarization, inference, text transformation, and chatbot development.

## Course Contents

### 1. Introduction
#### Types of LLMs
- **Base LLM**: Predicts the next word based on training data.
- **Instruction-Tuned LLM**: Fine-tuned to follow instructions using **Reinforcement Learning with Human Feedback (RLHF)**.

### 2. Guidelines for Prompting
#### Setup
- Load the API key and necessary Python libraries.
- Create a helper function to generate outputs.

#### Prompting Principles & Tactics
1. **Write Clear and Specific Instructions**
   - Use delimiters (e.g., `"""`, `<tag> </tag>`) for structure.
   - Request structured outputs (JSON, HTML, tables).
   - Verify conditions before generating output.
   - Use "Few-shot" prompting for better results.
2. **Give the Model Time to Think**
   - Specify step-by-step reasoning.
   - Use intermediate outputs before finalizing.

#### Model Limitations
- **Hallucinations**: LLMs may generate incorrect but plausible-sounding responses.
- Methods to reduce hallucinations are discussed.

### 3. Iterative Prompt Development
- Be clear and specific with instructions.
- Analyze undesired outputs and refine prompts.
- Iterate the process for better results.

#### Example: Marketing Product Description
- Adjust length, focus, and structure.
- Extract and format data in tables.

### 4. Summarization
- Summarize text with word/character limits.
- Focus on specific topics (e.g., pricing, shipping).
- Extract key information from multiple reviews.

### 5. Inferring
- Analyze sentiment (positive/negative).
- Identify emotions and extract named entities.
- Perform multiple tasks simultaneously.
- Infer topics and generate alerts for news monitoring.

### 6. Transforming
- Translate text into multiple languages.
- Adjust tone (formal, casual, professional).
- Convert between formats (e.g., JSON to table).
- Proofread and correct spelling/grammar.

### 7. Expanding
- Generate customized customer service emails.
- Personalize responses using customer sentiment.
- Control creativity with temperature settings:
  - **0.0**: Reliable and predictable outputs.
  - **0.3 - 0.7**: Some variety and creativity.

### 8. Chatbot Development
- Utilize the chat format for interactive conversations.
- Implement an **OrderBot** for a pizza restaurant:
  - Collect and display messages.
  - Maintain conversation context.
  - Generate structured order summaries in JSON.

## Conclusion
- **Key Principles**: Write clear instructions and allow reasoning time.
- **Iterative Development**: Improve prompts through testing and refinement.
- **LLM Capabilities**: Summarization, inference, transformation, expansion.
- **Practical Application**: Build chatbots and automated assistants.

## Getting Started
1. Clone the repository and install dependencies.
2. Set up the OpenAI API key.
3. Run Jupyter notebooks to explore the concepts interactively.

## References
- [Course Link](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/)