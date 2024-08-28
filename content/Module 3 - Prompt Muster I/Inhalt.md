## Applying Prompt Patterns I

Here's an example of the Question Refinement Pattern in action:

**Prompt:**

"For the next few questions, whenever I ask a question, suggest a better version of the question and ask me if I would like to use it instead."

**Sample Interaction:**

**My Question 1:** What is the best way to learn Python?

**ChatGPT:** Sure, here's a suggested question: 

"Considering my current programming experience, learning style, and desired applications, what are the most effective and engaging approaches to learning Python?" 

Would you like to use this question instead?

**My Response:** Yes

**ChatGPT:**  (Now using the refined question) ...

**My Question 2:** How do I make a website?

**ChatGPT:**  Sure, here's a suggested question: 

"To create a website that aligns with my specific purpose (e.g., portfolio, online store, blog), what programming languages, frameworks, and hosting options should I consider, and what are the recommended learning resources for each?" 

Would you like to use this question instead? 

**My Response:** No

**ChatGPT:** (Now using the original question) ... 

This pattern helps to:

* **Elicit more specific information:** The refined questions encourage me to think about my goals, constraints, and preferences.
* **Improve clarity:** The refined questions are often less ambiguous and more focused.
* **Guide the conversation:** By accepting or rejecting refinements, I can steer the interaction in a more productive direction. 

## Applying Prompt Patterns II

Here's an example of the Cognitive Verifier Pattern in action:

**Prompt:**

"When you are asked a question, follow these rules:

1. Generate a number of additional questions that would help more accurately answer the question.
2. Combine the answers to the individual questions to produce the final answer to the overall question."

**Sample Interaction:**

**My Question:** What is the best marketing strategy for a new artisanal bakery in a competitive city?

**ChatGPT:** To determine the best marketing strategy for your bakery, let's break down the question into smaller parts:

1. What is the bakery's unique selling proposition (USP)? What makes it stand out from competitors?
2. Who is the target audience? What are their demographics, interests, and baking preferences?
3. What is the competitive landscape? How many other bakeries are in the area, and what are their strengths and weaknesses?
4. What is the bakery's budget for marketing? 
5. What marketing channels are most effective for reaching the target audience (e.g., social media, local events, partnerships)?

Please provide answers to these questions so I can suggest a tailored marketing strategy for your bakery. 

**(I provide answers to the sub-questions)**

**ChatGPT:** Based on your responses, here's a potential marketing strategy for your bakery:

**(ChatGPT provides a comprehensive strategy, incorporating my answers to the sub-questions and drawing upon its knowledge of marketing best practices.)**

This pattern helps to:

* **Structure complex problems:** It breaks down a broad question into manageable sub-problems.
* **Gather relevant information:** The sub-questions prompt me to provide specific details that are crucial for a good answer.
* **Improve reasoning and accuracy:** By considering multiple factors and perspectives, the large language model can generate a more informed and nuanced response. 
