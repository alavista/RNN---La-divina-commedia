# Poetry generation (Deep Learning university project)

# Dataset 
- La divina commedia, Dante Alighieri

# Relevant implemented stuff
- Seq2Seq model with attention based on LSTM with input text tokenized at word level and char level (char level produce more rhyming verses)
- Rhyme encoder: we trained a classifier to discriminates the rhyming area of a word (from the accented vowel to the end) in order to create an encoder that put rhyming words close in a multi-dimension space. Intrisic evaluation of this encoder showed that it worked well but including this encoder in the text generation model didn't help the model to generate more rhymes.

# Evaluation
- Average Rhymeness
- Average Structuredness
- Average Hendecasyllables
- Plagiarism
