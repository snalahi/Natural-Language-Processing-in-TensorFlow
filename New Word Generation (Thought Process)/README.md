### New Word Generation as a Prediction Problem

Instead of generating new text, how about thinking about it as a prediction problem. Remember when for example you had a bunch of pixels for a picture,
and you trained a neural network to classify what those pixels were, and it would predict the contents of the image, like maybe a fashion item, or a
piece of handwriting. Well, text prediction is very similar. We can get a body of texts, extract the full vocabulary from it, and then create datasets
from that, where we make it phrase the Xs and the next word in that phrase to be the Ys. For example, consider the phrase, Twinkle, Twinkle, Little, Star.
What if we were to create training data where the Xs are Twinkle, Twinkle, Little, and the Y is star. Then, whenever neural network sees the words Twinkle,
Twinkle, Little, the predicted next word would be star. Thus given enough words in a corpus with a neural network trained on each of the phrases in that
corpus, and the predicted next word, 

#### New Word Generation with Small Corpus: https://www.coursera.org/learn/natural-language-processing-tensorflow/lecture/B80b0/notebook-for-lesson-1

