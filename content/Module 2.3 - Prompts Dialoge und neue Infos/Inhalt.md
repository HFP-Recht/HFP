## Step 1: Table of Contents

# Introduction
## The Importance of Introducing New Information
## How to Introduce New Information via Prompts

# Prompt Engineering Techniques
## Prompt Size Limitations
### Strategies for Managing Prompt Length
## Prompts as Tools for Repeated Use
### The Power of Conversational Prompts
### Iterative Refinement through Conversation
## Root Prompts
### Defining Ground Rules and Goals
### Simulating Training Data Cutoffs
### The Importance of Guard Rails

# Hands-on Lab
## Creating Prompts with New Information
### Answering Questions with New Information
### Performing Tasks with New Information 


## Step 2: Briefing Document: Prompt Engineering for Large Language Models

**Introduction:**

This document summarizes key concepts and techniques related to prompt engineering for large language models (LLMs) like ChatGPT. It emphasizes the importance of introducing new information to LLMs and explores various strategies for crafting effective prompts.

**Main Themes:**

- **Introducing New Information:** LLMs have a knowledge cutoff date and limited access to private or specific data sources. To enable reasoning on new information, users can directly embed relevant data within the prompt.
- **Prompt Size Limitations:**  LLMs have constraints on the amount of information they can process in a single prompt. Effective prompt design involves filtering, summarizing, and prioritizing essential information.
- **Prompts as Conversations:**  Treating prompts as a conversation allows for iterative refinement and problem-solving. By engaging in a back-and-forth with the LLM, users can guide it towards desired outcomes.
- **Root Prompts:** These are hidden prompts that set ground rules and goals for the LLM, influencing its behavior and responses. Understanding root prompts is crucial for customizing LLM experiences and implementing safety measures.

**Detailed Analysis:**

- **Fact 1: LLMs cannot access real-time information or private data.** To overcome this, users must provide the necessary context and data within the prompt itself.
- **Fact 2: Prompt length limitations necessitate careful selection and summarization of information.** Techniques like filtering, summarizing, and prioritizing key data points are essential for effective prompt design.
- **Fact 3:  Conversational prompts enable iterative refinement and problem-solving.** By engaging in a dialogue with the LLM, users can clarify their intent, provide feedback, and steer the conversation towards desired outcomes.
- **Fact 4: Root prompts define the fundamental rules and boundaries for LLM interactions.** They ensure ethical behavior, prevent harmful outputs, and can be leveraged to customize LLM experiences.

**Recommendations/Conclusions:**

- **Strategy 1:  Carefully curate and structure new information within prompts.** Provide sufficient context and prioritize essential data points for effective reasoning.
- **Strategy 2:  Embrace conversational prompts to iteratively refine outputs and overcome limitations.** Treat the LLM as a collaborative tool and engage in a back-and-forth dialogue.
- **Strategy 3:  Understand the role of root prompts in shaping LLM behavior and leverage them for customization and safety.** Consider potential vulnerabilities and implement appropriate guardrails. 
