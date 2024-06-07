# Few-Shot-Emotion-Classifier
We try to accurately predict the emotion in the input sentence, with a small dataset of <50 examples!

## Here is the main solution :
- Flan T5 from HuggingFace is our language model.
- We implement LORA to reduce training time significantly.
- Various data generation techniques like Backtranslation and Adversarial methods to augment the dataset.

## I also tried :
- GPT-2 and BERT as models, which didn't do great as they are just slightly more complex than Encoders with attention.
- LLM based data-generation, which was too expensive with GPT-3.5



