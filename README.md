# ThinkTwice
Prompting configurations used in the "Think Twice" method, as presented in MICAI 2025. 
This folder contains all the prompts used in different experimental settings (zero-shot, zero-shot with task context, label confirmation, few-shot with static examples, and few-shot with dynamically selected examples).

This folder contains the prompts used in different configurations described in the paper:

- **zero_shot.txt**: Direct classification without context.
- **zero_shot_context.txt**: Includes a brief definition of the classification task.
- **label_confirmation.txt**: The base classifier's prediction is provided for confirmation.
- **few_shot_examples.txt**: Includes manually selected examples for few-shot prompting.
- **few_shot_dynamic/**: Contains dynamically selected examples based on the attraction force model.

All prompts were tested on the EXIST and AMI datasets. The formatting and examples are consistent with the original experiments.


