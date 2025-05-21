Custom Tokenizer:
-->Patterns for emoticons, contractions, words and punctuatons were illustrated
-->Function developed to count repeated characters
-->Function to separate individual words as tokens
-->Stop words removed
-->used tags for parts of speech according to suffixes

Lemmatizer:
-->Developed identification for noun, verb and adjective
-->Changed participle and continuous forms of verbs by removing -ed,-ing etc.
-->Changed plural forms of nouns into singular
-->Changed comparative and superlative forms of adjectives by removing -er,-est etc.

Character Repeat Normalization
In informal text, repeating characters, such as "soooo happy" or "noooooo". These variations can hinder NLP models, as they increase vocabulary size and introduce meaningless terms.

Importance:
Reduces Vocabulary Size: By normalizing repeated characters (e.g., converting "soooo" to "so"), we decrease the number of unique tokens, simplifying the model's vocabulary.
Improves Model Performance: Normalization enhances the accuracy of downstream tasks like sentiment analysis and hate speech detection by aligning expressive variations with their standard forms.
Enhances Consistency: It ensures that semantically identical words are treated uniformly, improving the reliability of text analysis.

POS-Tagged Lemmatization
Lemmatization reduces words to their base or dictionary form (lemma), considering the word's context and part of speech (POS). For instance, "running" can be lemmatized to "run" when identified as a verb.
Importance:
Contextual Accuracy: Incorporating POS tags allows lemmatizers to distinguish between different grammatical forms, ensuring accurate base forms are derived.
Improved Text Normalization: Accurate lemmatization aids in standardizing text, which is vital for tasks like information retrieval and machine translation.
Enhanced Understanding: By recognizing the correct lemma, models can better grasp the underlying meaning of words in context, leading to more accurate NLP applications.

