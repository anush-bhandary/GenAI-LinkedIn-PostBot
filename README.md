# GenAI-LinkedIn-PostBot
This tool analyzes a LinkedIn influencer's past posts and assists in generating new content that aligns with their writing style.

![tool](https://github.com/user-attachments/assets/007cdc90-7683-4163-a886-593aac4fd5d0)

Suppose Navya is a LinkedIn influencer seeking assistance in crafting her upcoming posts. She can input her previous LinkedIn content into this tool, which will analyze and extract key topics. Navya can then choose a topic, preferred length, language, and simply click the Generate button to create a new post that aligns with her unique writing style.


# Technical Architecture

![architecture jpg](https://github.com/user-attachments/assets/293e6138-30c7-4cb1-b1d1-b36d2202f14c)

1. Stage 1: Gather LinkedIn posts and extract key attributes such as topic, language, and post length.
2. Stage 2: Use the selected topic, language, and length to generate a new post. A few relevant past posts matching those criteria are used as examples (few-shot learning) to guide the LLM in capturing the writing style effectively.


 #  Acknowledgements
 Credits to [Codebasics Inc.](https://www.codebasics.io/) for the foundational ideas and guidance.  
© Codebasics Inc. All rights reserved.
