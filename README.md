# ToolReflection

This repository contains supplementary materials for the paper *"ToolReflection: Improving Large Language Models for Real-World API Calls Through Self-Generated Data."*

In this paper, we conduct experiments using the following frameworks: `GPT4Tools`, `ToolAlpaca`, and `ToolBench`.

The repository provides our code, including generation prompts, error generation scripts, and augmented datasets for each framework. These materials are organized into separate folders, each containing:
- The original code for fine-tuning and evaluating the models.
- Our modifications and enhancements.
- Code for generating tool invocation chains with errors and their corrections (the **ToolReflection** approach).

Additionally, we introduce specific improvements for each framework. For example:
- In the `GPT4Tools` folder, we include:
  - Code for augmenting the dataset with additional data, such as `GPT4FakeTools`.
  - Additional benchmarks for more realistic evaluations, specifically `GPT4Tools-OOD` and `GPT4Tools-OOD-Hard`.


