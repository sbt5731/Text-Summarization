# Text Generation using Language Models

This repository contains a code snippet that demonstrates text generation using a language model. The code focuses on the concepts of one-shot, few-shot, and zero-shot inferences, showcasing how to create prompts, generate text, and compare the generated output with human-written summaries.

## Code Overview

The code snippet is designed to showcase the following concepts:

1. **One-shot Inference:** This section demonstrates how to create a prompt using a single example and generate text based on that prompt.

2. **Few-shot Inference:** This section showcases the process of creating prompts using multiple examples and generating text accordingly.

3. **Zero-shot Inference:** This section illustrates how to generate text without providing any explicit examples in the prompt. Instead, the model generates text based on a general instruction or context.

The dataset used for the examples includes dialogues and summaries, which are used to construct prompts for the language model.

## Usage

1. **One-shot Inference:**
   - Set the `example_indices_full` and `example_index_to_summarize` variables to specify the indices of examples to use as prompts.
   - Construct a prompt using the specified example indices using the `make_prompt` function.
   - Generate text based on the prompt using the language model.
   - Compare the generated output with the human-written summary.

2. **Few-shot Inference:**
   - Similar to one-shot inference, set `example_indices_full` and `example_index_to_summarize` to define examples for prompts.
   - Use the `make_prompt` function to create a prompt with multiple examples.
   - Generate text using the language model and compare the output with the human-written summary.

3. **Zero-shot Inference:**
   - Create a prompt without providing specific examples.
   - Generate text based on the provided context or instruction.
   - Examine the generated output to see how the model responds to the context.

## Requirements

- Python (>=3.6)
- Transformers library (Hugging Face)


