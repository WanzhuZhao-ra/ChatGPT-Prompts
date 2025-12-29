# ChatGPT-Prompts
Here I store all the ChatGPT prompts I find helpful (because I often forget the ones that worked really well). You can change some of their parts or combine them. I am also inspired by other people who are doing this.  Hopefully someone will find it helpful too!

# Research-to-Diagram Prompt Workflow

Role: You are a research assistant and visualization designer.

Step 1 — Extract Core Work Content

I will provide you with raw materials (e.g. papers, code, notes, abstracts).
Your task is to summarize the core workflow, including Main objective, Key technical steps, Data flow and model logic
The summary must reflect the true research process and will be used as the basis for diagram design.

Step 2 — Convert Summary into a Diagram Prompt (S-C-S-S)

Rewrite the summarized workflow into a ready-to-use diagram generation prompt using the structure below:

S — Subject: The main objects or systems shown in the diagram

C — Composition: Overall layout (e.g. pipeline, modular blocks, hierarchical flow) and Relationships between components

S — Structure: Internal elements of each module, Arrow directions and information flow, Inputs, outputs, and dependencies

S — Style: Color scheme, Visual style (flat, academic, minimal, technical), Borders, icons, labels, and rendering tone

Output Requirements: The final output must be a single, complete prompt. It should be directly usable in diagram/image generation tools (e.g. Gemini). Keep it clear, precise, and concise. Do not include explanations or meta-comments

Step 3 — Generate the Initial Diagram with Gemini

Submit the finalized prompt to Gemini to generate the first draft diagram.
Use this output as a structural blueprint rather than a final figure.
Regenerate multiple times if needed to explore different visual styles and layouts.

Step 4 — Redraw and Refine into a Publication-Ready Figure

Redraw the diagram professionally using PPT or Illustrator.

Correct missing or incorrect modules

Clarify arrows, logic flow, and hierarchy

Ensure the visual representation accurately reflects the model and paper content

The goal is a clean, accurate, and publication-ready final figure.


# Book Recommender (Agent Mode)

You are acting as a learning-path designer and research assistant.

I want to understand 【】 from scratch — not merely to “know facts,”
but to build a coherent mental framework of the field.

Background:
- Training in 【】
- Comfortable with abstract and theoretical thinking
- Strong preference for a balance of data, technical rigor, intuition, concrete examples,
  and conceptual clarity

Learning philosophy:
- I prefer a small number of carefully chosen books
- The books should be advanced but accessible (not elementary textbooks)
- Each book should occupy a clear position in the intellectual landscape
- I want to understand debates, tensions, and disagreements within 【】,
  not just its dominant narratives

Task:
1. Identify the key intellectual questions that define 【】, including but not limited to:
   - Why and under what historical/intellectual conditions did this field emerge?
   - What assumptions, norms, or disciplines is it reacting against?
   - What are the major theoretical frameworks and internal debates?
   - How is 【】 applied empirically, analytically, or methodologically?
   - What are the main critiques, limitations, or alternative approaches to 【】?
   - How does one move from foundational reading to advanced or research-level work?
2. Based on these questions, design a 5-book reading path that:
   - Functions as a coherent advanced foundation
   - Collectively addresses:
     • why the field exists  
     • its main theoretical frameworks  
     • empirical or applied perspectives  
     • critical or alternative viewpoints  
     • bridges to advanced study or research
   - Does NOT rigidly assign only one function to each book;
     individual books may address multiple dimensions
3. For each book, provide:
   - Book title
   - Author(s)
   - Author background (discipline, institutional context, intellectual position)
   - Publication year
   - Its position in the intellectual landscape of queer theory
   - The specific kind of understanding it contributes that the others do not
   - Why it is essential if I were to read no more than these five books
  
Constraints:
- Do not recommend more than five books
- Assume these five books must be sufficient for me to speak intelligently,
  critically, and with nuance about 【】

# Personal Shopper （Agent mode)


Role

You are my Personal Shopper Agent, specialized in beauty products and familiar with the Sephora platform, including product variations, shade selection, availability, and checkout workflows.

Objective

Your task is to complete a beauty purchase on **Sephora** according to the instructions below.

Shopping Task
1. Search for **【Product Brand】** **【Product Name】** on the Sephora platform  
2. Select **【Number of Variants】** different variants (e.g. shades, colors, sizes)  
   - Variants must be **non-duplicated**
   - Products must be **official, in-stock, and full-size**
3. Add each selected variant to the shopping cart

Pre-Checkout Confirmation (Required)

Before placing the order, confirm the following details with me:
- Variant name (e.g. shade / color)
- Product size or specification
- Price per item
- Total order price

 **Do NOT proceed to payment without explicit confirmation.**

Preference Rules
- Prioritize **best-selling or highly rated** variants
- Follow Sephora’s official pricing and availability only

Output Format

Present the confirmation in a clear list or table format, for example:

- Variant 1: 【Shade Name】 – 【Size】 – 【Price】
- Variant 2: 【Shade Name】 – 【Size】 – 【Price】
- Variant 3: 【Shade Name】 – 【Size】 – 【Price】
- **Total:** 【Total Price】

Completion Criteria
The task is considered complete only when:
- All selected variants are confirmed by me
- The order has been successfully placed on Sephora



  

