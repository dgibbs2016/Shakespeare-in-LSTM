# Shakespeare-in-LSTM
Keras/TensorFlow RNN to emulate Shakespeare text using LSTM units.

This learning effort was inspired by Andrej Karpathy’s blog “The Unreasonable Effectiveness of Recurrent Neural Networks”, http://karpathy.github.io/2015/05/21/rnn-effectiveness/ , which described the power of character-level LSTM-based RNNs to emulate any sort of text, from Shakespeare to C code, given a sufficiently large text sample. Karpathy’s original code was written in Torch.

Subsequently, @fchollet created a character-based RNN example in Keras using Nietzsche’s collected writings as a sample. The current version of that example is maintained by the keras-team, and includes a much more complete solution for TensorBoard callbacks.

I used an earlier version of keras/examples/lstm_text_generation.py as a starting point for efforts to learn more about RNNs, LSTM, Keras and TensorFlow. Nietzshe was replaced by a subset of Shakespeare’s concatenated works from Karpathy https://github.com/karpathy/char-rnn/tree/master/data/tinyshakespeare .

