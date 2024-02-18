# The-Food-Product-Nutrition-Assistant

This guide provides detailed instructions on how to create a Food Product Nutrition Assistant using Custom GPT, as seen in work presented in the CHI24 paper titled "Integrating Expertise in LLMs: Crafting a Customized Nutrition Assistant with Refined Template Instructions." The process involves configuring a Custom GPT model with specific instructions, conversation starters, and knowledge sources, including a unique dataset on Nutrition Facts Labels. The model is designed to deliver personalized, detailed explanations of food products, clarifying their suitability relative to dietary goals in a structured format reviewed by registered dietitians.

![Example Image](/images/GPTCustomized.pdf "This is an example image")

## Step-by-Step Instructions:

### 1. Initialize Custom GPT Model
Begin by creating a new Custom GPT model on the ChatGPT platform.

### 2. Access Configuration Settings
Navigate to the 'Configure' setting of the Custom GPT model. 

### 3. Incorporate Instruction Template
Within the 'Instructions' box, paste the provided [Instruction Template](./Instructions/Custom_GPT_Instructions.pdf). This template outlines the operational framework and response behavior for the GPT, aligning with the objectives registered dietitians.

### 4. Upload Essential Knowledge Sources
Import knowledge sources into the ['Knowledge'](./Knowledge/) section. 

### 5. Integrate Nutrition Facts Label Dataset
Upload a dataset containing Nutrition Facts Labels for the products you wish to analyze. This step enhances the GPT's capability to offer specific nutritional insights. 

### 6. Engage with Custom GPT
Interact with the GPT by prompting it with a specific product and dietary goals. The model will utilize the configured instructions, knowledge sources, and dataset to generate tailored nutritional advice.

By following these steps, you will successfully create a Food Product Nutrition Assistant Custom GPT, providing food product explanations based on the design guidelines outlined in the CHI24 paper. 




