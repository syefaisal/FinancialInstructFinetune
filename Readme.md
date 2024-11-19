I finetuned another LLM on financial Q&A.

From scratch.

Implementation details:
• 355M param LLM
• 6K training samples
• 0.67 training loss
• 0.90 validation loss

I used a single A100 and it took ~7 minutes.

Really cool to see the before and after results.

Before: LLM generates random text.

After: LLM generates an answer attempt.

Shout out to 
@rasbt
 for the code.
