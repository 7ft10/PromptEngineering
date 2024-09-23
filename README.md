# Prompt Engineering

Interacting with AI to achieve results requires asking the right questions, often referred to as "prompts." The way you phrase a question or provide instructions can greatly influence the response you receive. This process of structuring and refining inputs is known as Prompt Engineering.

This guide will explain prompt engineering, why it is essential, and how you can master asking questions about AI systems. We will dive into the techniques, strategies, and best practices for crafting effective prompts and provide examples to illustrate how different prompts can yield vastly different outcomes.

Prompt engineering is an emerging discipline that efficiently develops optimized prompts to apply language models to various tasks. Prompt engineering helps researchers understand the abilities and limits of large language models (LLMs). Using various prompt engineering techniques, you can often get better answers from the foundation models without spending effort and time retraining or fine-tuning them.

Note that prompt engineering does not involve fine-tuning the model. The weights/parameters are adjusted using training data to optimize a cost function in fine-tuning. Model fine-tuning is generally an expensive process in terms of computation time and actual costs. Prompt engineering attempts to guide the trained foundation model (FM) to provide more relevant and accurate answers using various methods, such as better-worded questions, similar examples, intermediate steps, and logical reasoning.

Prompt Engineering leverages the principle of “priming”: providing the model with a context of a few (3-5) examples of what the user expects the output to look like so that the model mimics the previously “primed” behaviour. By interacting with the LLM through a series of questions, statements, or instructions, users can effectively guide the LLM's understanding and adjust its behaviour according to the specific context of the conversation.

In short, prompt engineering is a new and essential field for optimizing how you apply, develop, and understand language models, especially large ones. At its core, it is about designing prompts and interactions to expand what language technologies can do, address their weaknesses, and gain insights into their functioning. Prompt engineering equips us with strategies and techniques for pushing the boundaries of what is possible with language models and their applications.

## Why is it relevant?
The key ideas are:
- Prompt engineering is the fastest way to harness the power of large language models.
- Prompt engineering optimizes how you work with and direct language models.
- It boosts abilities, improves safety, and provides understanding.
- Prompt engineering incorporates various skills for interfacing with and advancing language models.
- Prompt engineering enables new features like augmenting domain knowledge with language models without changing model parameters or fine-tuning.
- Prompt engineering provides methods for interacting with, building, and grasping language models' capabilities.
- Higher-quality prompt inputs lead to higher-quality outputs.

## What is Prompt Engineering?
Prompt Engineering is designing and refining questions or commands to elicit the most useful, relevant, and accurate responses from an AI system. AI models work by interpreting the inputs they receive, and the structure, clarity, and context of these inputs determine the quality of the outputs.

Without prompt engineering, the interaction with AI can feel frustrating, with responses that are either too vague, too technical, or off-topic. A well-engineered prompt can help direct the AI to provide answers that are concise, informative, and applicable to your needs.

Example:

Poor Prompt: "What is AI?"

This query is too broad and may result in an overly general answer.

Good Prompt: "Can you explain how AI is used in retail to improve customer service?"

This query is specific and asks for context, resulting in a more focused and useful response.

## Why is Prompt Engineering Important?
Understanding how to craft a prompt that the AI can easily interpret is crucial for several reasons:

Accurate Responses: Well-structured prompts result in accurate and relevant answers, saving time and reducing confusion.

Efficiency: By asking precise questions, users can obtain specific answers quickly, without needing to ask follow-up questions for clarification.

Problem-Solving: Prompts that are clear and well-defined help AI understand the scope and complexity of the issue, allowing it to provide better solutions or explanations.

Customisation: AI can be tailored to different contexts, industries, or situations through prompt engineering, enhancing its practical utility.

## Prompt Engineering Techniques
Here are various techniques for prompt engineering that you can use to get better responses from AI systems:

1. Be Clear and Specific
One of the most fundamental aspects of prompt engineering is clarity. The more specific your prompt, the more focused the response will be.

AI models rely on patterns in data to understand and respond. A specific prompt helps the AI hone in on the most relevant information, avoiding ambiguous or irrelevant answers.

Example:

Too Broad: "Tell me about marketing."

Specific: "How does social media marketing contribute to brand awareness for small businesses?"

2. Provide Context
AI works better when you give it background or context to understand the problem or subject area you're inquiring about.

Without context, AI might generate responses that are technically correct but not relevant to your specific needs.

Example:

Lack of Context: "How do I improve customer service?"

Contextualized: "In the e-commerce industry, how can AI chatbots improve customer service by handling customer queries?"

3. Ask Multi-Step or Structured Questions
For complex queries, it is often helpful to break down your questions into smaller parts or multi-step instructions.

If the AI is asked too many things at once, the response may lack detail or miss important aspects. Structuring your prompt in parts allows the AI to address each element methodically.

Example:

Unstructured: "How do I improve sales and marketing?"

Structured: "Can you first explain how I can improve my online marketing strategy? Then, how can I use data analytics to improve sales?"

4. Role-Playing and Instruction-Based Prompts
Asking the AI to adopt a role or follow specific instructions can significantly enhance the relevance of its response.

When given a role, the AI understands the perspective and context more clearly, leading to more tailored and practical advice.

Example:

General: "What is machine learning?"

Role-Based Prompt: "Imagine you are explaining machine learning to a high school student. Can you explain the concept in simple terms?"

5. Specify the Desired Output Format
If you want a specific type of answer, such as a summary, list, or detailed explanation, it’s crucial to include this instruction in your prompt.

AI can generate different levels of detail, so specifying the format helps control the depth and structure of the response.

Example:

No Output Format: "Tell me about AI in healthcare."

With Output Format: "Can you summarize the top three ways AI is transforming healthcare, and give a detailed explanation of how it assists in diagnosis?"

6. Iterate and Refine
Often, the first prompt you use might not yield the perfect result. Instead of giving up, refine your prompt by adding detail or narrowing the focus.

AI learns from each prompt, and refining your approach allows the system to better understand your needs over time.

Example:

First Attempt: "How does AI improve manufacturing?"

Refined Prompt: "What are three examples of how AI enhances efficiency in automotive manufacturing?"


In short we call this “The ASCC Framework” (Action, Subject, Context, Condition)
Action (Instruction): Defines the specific action you want the AI to perform, setting the expectation for the response.

Subject: Focuses the prompt on the specific entity or concept the action applies to.

Context: Provides the background, allowing AI to tailor its response to a specific situation or audience.

Condition: Specifies any constraints or additional parameters to ensure the answer meets particular requirements.

 

diagram goes here

Best Practices for Prompt Engineering
To make the most of AI systems, it's important to follow certain best practices when designing your prompts.

1. Keep Prompts Concise but Informative
Avoid overly long or convoluted sentences. Keep your questions straightforward but ensure they contain the necessary details.

Example: Instead of "Can you explain how companies can use AI to increase sales and customer engagement, especially when dealing with online markets?" Instead ask, "How can AI help increase online sales and improve customer engagement?"

2. Choose the Right Type of Question
Use open-ended questions when exploring new ideas or seeking creative insights. Use closed-ended questions for specific information.

Example:

Open-Ended (for exploration): "What are the future trends of AI in the tech industry?"

Closed-Ended (for specifics): "What year was OpenAI founded?"

3. Use Positive Prompts to Guide Output
Instead of framing a question negatively or with uncertainty, use positive, action-oriented language to guide AI toward useful responses.

Example: Instead of "Can AI fail in customer service?" ask "How can AI be optimized to provide excellent customer service?"

4. Ask for Step-by-Step Processes for Complex Queries
For tasks that require multiple steps, instruct the AI to provide a breakdown of each part of the process.

Example: "Can you give me a step-by-step guide on how to set up a data analysis pipeline using Python?"

5. Test and Adjust Your Prompts
If you are not satisfied with the initial response, don’t hesitate to tweak your prompt by changing the structure, adding more detail, or narrowing the focus.

Example: If "How do I start a business?" doesn’t give you enough information, refine it to "Can you provide a detailed business plan template for a small retail startup?"

6. Provide Examples to Clarify Complex Requests
When dealing with complex or technical subjects, providing an example within your prompt can clarify your expectations.

Example: "Can you explain deep learning using an example of how it’s applied in autonomous vehicles?"

## Some General Guidance
AWS provides general guidance when creating and engineering prompts: 
- Be clear and concise
- Include context if needed
- Use directives for the appropriate response type
- Consider the output in the prompt
- Start prompts with an interrogation 
- Provide an example response 
- Break up complex tasks
- Experiment and be creative
- Use prompt templates 
