﻿# scratch-torch-gpt

## Intro:
In this repo, I re-implement the GPT model, which is used in the famous ChatGPT. The model, however, is not the latest technologies of ChatGPT but rather the architecture from the early time like GPT-2 GPT-3. The model is decoder only taking from the Transformer model from "Attention is all you need" paper (Ashish Vaswani et al, 2017). Now, there are some details or features for the implementation:
- The code is from Andrej Karpathy youtube tutorial for building GPT with slight modification for efficiency
- I trained the model with character-by-character tokenizer, not sub-word tokenizer so the model actually can't generate lots of meaningful sentence. It manage to generate English tho.
- To make things more interesting, I also train another model on Vietnamese language with Truyen Kieu dataset. (Because I'm Vietnamese, I want to see how the model perform in Vietnamese)

## Truyen-Kieu-GPT
The model is similar to the English language version but can generate six-eight poem style since Truyen Kieu is actually a poem written in six-eight style
