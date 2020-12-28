
Implementing a neural machine translation model that inputs an English sentence and converts to German.<br />

Pipeline of the model:
- Tokenizing the input data.
- Bucketing the  tokenized sequence to speed up training.
- LSTM model as an encoder and a decoder along with attention layers between them.
- Minimum Bayes Risk decoding to generate the translated output.
