# Guided Decoder

## Overview

Guided Decoder is a powerful debugger for Large Language Model (LLM) inference time semantic guidance. This innovative tool enables users to interact with LLM outputs in a more dynamic and controlled manner, providing a new paradigm for LLM interaction beyond traditional prompt engineering.

## Key Features

### Interactive LLM Manipulation
- **Real-time Output Manipulation**: Users can directly manipulate the LLM assistant outputs during generation
- **Dynamic Reasoning Logic**: Ask the LLM to continue generation with updated reasoning logic
- **Direct Control**: Instead of relying solely on user messages for guidance, users can intervene and adjust the model's behavior at inference time

### Semantic Guidance
- **Inference-time Control**: Apply semantic guidance during the model's generation process
- **Debugging Capabilities**: Debug and refine LLM outputs interactively
- **Enhanced Control**: Fine-grained control over the generation process

## Use Cases

- **Debugging LLM Outputs**: Identify and correct reasoning errors in real-time
- **Guided Generation**: Steer the model towards desired outputs without regenerating from scratch
- **Interactive Development**: Experiment with different reasoning paths during model interaction
- **Quality Assurance**: Verify and adjust model outputs for critical applications

## Benefits

- **Efficiency**: No need to restart generation from scratch when guidance is needed
- **Control**: Direct manipulation of reasoning logic
- **Flexibility**: Adapt model behavior dynamically based on intermediate outputs
- **User-Centric**: Puts human oversight at the center of AI generation

## Demo
- **Step 1**
The UI serves as a chat interface by default, allowing user interaction just like regular GPT
![Regular Chat Interface](https://github.com/JamesChenSH/JamesChenSH/blob/main/image%20(1).png)

- **Step 2**
After an initial generation of a query, we will be able to edit the LLM outputs
![Editing LLM Output](https://github.com/JamesChenSH/JamesChenSH/blob/main/image%20(2).png)

- **Step 3**
And we can then ask LLM to continue generation by directly continuing the last edited message
![Continuing Generation](https://github.com/JamesChenSH/JamesChenSH/blob/main/image%20(3).png)

- **Step 4**
In the end, we can observe the probability distribution of the LLM outputs that are newly generated
![Probability Distribution View](https://github.com/JamesChenSH/JamesChenSH/blob/main/image%20(4).png)
