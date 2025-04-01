# Transformer to gpt2

- Transformer is encoder-decoder, gpt2 is decoder only
- transformer is seq2seq, gpt2 is seq2token
- transformer uses sinusoidal positional embedding, gpt2 learns positional embeddings
- transformer applies layernorm after residual connection, gpt2 applies before
- transformer decoder uses cross attention, gpt2 decoder uses self attention
- transformer can use anything, gpt2 uses gelu activation

# gpt2 to gpt3

gpt3 has literally the same architecture, just 100 times bigger. More layers, more training data, more gpu. no other changes