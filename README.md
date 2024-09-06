## Supporting files for cs224u homework assignment on sentiment classification
`synthetic_data-dict-dynasent_r1_r2` contains the first 1000 entries in dynasent_r1 and dynasent_r2 datasets that have been given to `gemma-2-2b-it` model to generate data for fine-tuning.
`outputs/checkpoint-5000` contains LoRA checkpoint after 5000 iterations on the synthetic dataset.

**Generation prompt:**
```
<start_of_turn>user
Rate the text as either positive, negative or neutral.
Text: {text}<end_of_turn>
<start_of_turn>model
The text is **{label}** because
```
