# dl-math-word-problem-solving
Using Seq2Seq Model with Attention and Transformer Model to convert simple Math Word Problems to their corresponding Equations.

Introduction
 The aim with the project is to use Deep Learning to automatically convert simple math word 
problems, such as “If Andy has 5 apples and Jerry eats 1, how many are left?”, to a math 
equation: “x = 5 - 1”.
 We have experimented with seq2seq models with Attention, and Transformer model to 
accomplish this task.
 The project is broadly divided into two parts:
 1. A baseline, where we use a simple list of generated problems, such as “Two hundred 
fifty plus Three thousand nine hundred” to measure the seq2seq model performance.
 2. We then take a dataset of ~38k single variable math word problems and train a 
seq2seq and Transformer model and compare their performance.
Metrics used
 We used two metrics to evaluate the performance of all our models:
 1. Accuracy: In order to see how exact the predictions of the model are
 2. Corpus BLEU (Bilingual Evaluation Understudy) score: A metric developed 
specifically to for auto-translation systems, BLEU score compares n-grams of 
the candidate and reference translation, so even if the translation is not an 
exact match, the score is not zero.


References:
1. https://www.tensorflow.org/tutorials/text/transformer#top_of_page
2. https://www.tensorflow.org/tutorials/text/nmt_with_attention#top_of_page
3. https://web.stanford.edu/class/cs224n/reports/custom/15843468.pdf

