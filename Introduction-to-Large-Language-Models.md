# Introduction to Large Language Models

## Instructor
- **Instructor:** John Ewald, Google Cloud Training Developer

## Course Objectives
- Define Large Language Models (LLMs)
- Describe LLM Use Cases
- Explain Prompt Tuning
- Describe Google’s Gen AI Development tools

## Large Language Models (LLMs)
- Subset of Deep Learning.
- Intersects with Generative AI.
- Capable of producing new content (text, images, audio, synthetic data).

## Key Features of LLMs
- **Large:** Enormous training dataset, petabyte scale.
- **General-purpose:** Solve common language problems.
- **Pre-trained and Fine-tuned:** Initially trained for general purposes, then tailored for specific aims.

## Benefits of Large Language Models
- Single model for different tasks.
- Minimal field training data required.
- Continuous performance improvement with more data and parameters.

## PaLM (Pathways Language Model)
- 540 billion-parameter model.
- Dense decoder-only Transformer.
- Leverages Pathways system for efficient training.

## Evolution of Programming
- Traditional programming: Hard-coded rules.
- Neural networks: Predictions based on data.
- Generative models: Users can generate content.

## LLM Development vs Traditional ML
- LLM: No need for expertise, training examples, or model training.
- Prompt design is crucial.

## Text Generation Use Case: Question Answering (QA)
- Traditional QA: Requires domain knowledge.
- Generative QA: Model generates free text based on context.

## Prompt Design vs Prompt Engineering
- **Design:** Tailored to the task. Generalized knowledge is sufficient, for eg. Converting English text to French
- **Engineering:** Improves performance. Domain-specific knowledge is required to get more detailed and accurate result

## Types of LLMs
- **Generic Language Models:** Predict next word based on language.
- **Instruction Tuned:** Trained to respond to specific instructions.
- **Dialog Tuned:** Trained for dialog responses.

## Chain of Thought Reasoning
- Models often give better answers when providing reasoning for the answer.

## Task-Specific Tuning and Vertex AI
- Vertex AI provides task-specific foundation models.
- Task-specific tuning improves reliability.

## Fine-tuning and Parameter-Efficient Tuning
- **Fine-tuning:** Adapt model to a new domain.
- **Parameter-Efficient Tuning:** Tunes add-on layers for custom data without altering the base model.

## Generative AI Studio and PaLM API
- Tools for exploring, customizing, and deploying generative AI models.
- PaLM API integrates with MakerSuite for quick prototyping.

## Conclusion
- Large Language Models offer versatility and efficiency.
- Applications in various domains with minimal field training data.
