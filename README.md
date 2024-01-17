# Generative AI Use Case: Summarize Dialogue

Welcome to the practical segment of our course, focusing on dialogue summarization using generative AI. In this lab, you'll explore how input text influences a model's output and delve into prompt engineering to steer it towards desired tasks. By experimenting with zero-shot, one-shot, and few-shot inferences, you'll embark on a journey into prompt engineering, discovering how it can augment the generative capabilities of Large Language Models (LLMs).

# Table of Contents
1. Set up Kernel and Required Dependencies
Ensure the correct kernel is active. Install necessary packages for PyTorch and Hugging Face transformers.
2. Summarize Dialogue without Prompt Engineering
Generate dialogue summaries using FLAN-T5 from Hugging Face without any prompt engineering.
3. Summarize Dialogue with an Instruction Prompt
Enhance the summarization task using instruction prompts and observe changes in the model's output.
3.1 Zero Shot Inference with an Instruction Prompt
3.2 Zero Shot Inference with the Prompt Template from FLAN-T5
4. Summarize Dialogue with One Shot and Few Shot Inference
Experiment with one-shot and few-shot inferences to see their impact on dialogue summarization.
4.1 One Shot Inference
4.2 Few Shot Inference
5. Generative Configuration Parameters for Inference
Explore how different configuration parameters affect the model's output.
# 1 - Set up Kernel and Required Dependencies
First, select the appropriate kernel. Then, install the required packages to utilize PyTorch, Hugging Face transformers, and datasets.

# 2 - Summarize Dialogue without Prompt Engineering
In this section, generate a summary of a dialogue using the pre-trained FLAN-T5 model. Compare the output to baseline human-generated summaries.

# 3 - Summarize Dialogue with an Instruction Prompt
Instruction prompts are vital for steering the model towards specific tasks. This section explores zero-shot inference with instructional prompts and how different prompt formulations impact the output.

# 4 - Summarize Dialogue with One Shot and Few Shot Inference
Discover the effects of one-shot and few-shot inferences on dialogue summarization. Analyze how providing examples within the prompt affects the model's performance.

# 5 - Generative Configuration Parameters for Inference
Manipulate various configuration parameters of the generate() method to see their influence on the output. Experiment with parameters like max_new_tokens, do_sample, and temperature to understand their impact on dialogue summarization.
