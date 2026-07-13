# 📐 Prompt Library for AI Designers

An open-source collection of prompt patterns, system instructions, and LLM methodologies tailored for Product Design, UI/UX, and User Research. 

## The Problem

As AI integrates into every facet of software, the gap between engineering-driven AI tools and human-centered design is widening. Product Designers need predictable, scalable ways to leverage Large Language Models (LLMs) and diffusion models in their daily workflows. 

This repository treats prompts as **design systems**. Instead of random text strings, these prompts are structured, tested, and version-controlled to ensure consistent outputs for UX writing, asset generation, and user simulation.

## What's Inside

This library is organized into four core domains:

*   **`/personas`**: System prompts that instruct an LLM to behave as specific, highly detailed user archetypes for early-stage conversational testing and journey mapping.
*   **`/ui-assets`**: Structurally precise prompts for diffusion models (Midjourney, DALL-E) to generate UI-safe assets, empty states, and vector-style iconography without hallucinations.
*   **`/ux-writing`**: Frameworks for generating interface copy, error messages, and onboarding flows that strictly adhere to specific brand voices and character limits.
*   **`/ai-patterns`**: System instructions for designing "AI-First" UI features, including how to prompt an AI to return structured JSON for UI population.

## Structure of a Prompt Entry

Every prompt in this library follows a standardized documentation format to ensure repeatability:

1.  **Objective:** What this prompt achieves.
2.  **The Prompt:** The exact text/variables to use.
3.  **Context & Variables:** Which parts of the prompt need to be modified for your specific project (denoted by `[BRACKETS]`).
4.  **Anti-Patterns / Negative Prompts:** What to explicitly tell the model *not* to do.
5.  **Expected Output:** An example of a successful generation.

## Why Contribute? (The 1% Better Philosophy)

Mastering AI as a designer requires daily, incremental practice. This repository is built on the philosophy of compounding growth. 

By taking 15 minutes a day to test a new prompt, refine a constraint, or document an edge case, you build a public track record of your evolving craft. You aren't just generating activity; you are building foundational infrastructure for the open-source design community.

## How to Use & Contribute

1.  **Fork the repository** and clone it locally.
2.  **Explore the categories** and test the prompts in your LLM of choice (ChatGPT, Claude, Midjourney).
3.  **Iterate and Document:** Find a way to make a prompt yield more consistent results? Modify it. 
4.  **Submit a Pull Request:** Add your refined prompt or a completely new use-case following the standardized template in `/docs/template.md`.

