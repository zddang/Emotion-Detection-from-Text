# Emotion-Detection-from-Text
Use classification models to identify 1 among 4 emotions (joy, sadness, fear, and anger) for the tweet dataset.
Hybrid approaches: adopts a mixture of rule-based and ML approaches.

## Clean Text approaches:
In the ‘text_clean’ function, I used different techniques to preprocess the input text dat. Here are the key techniques utilized:
*	Lowercasing: Convert all text to lowercase to ensure uniformity.
*	Removal of Line Breaks: Line breaks in the text are removed to ensure a seamless flow of content.
*	Hyperlink Removal: Any hyperlinks or URLs present in the text are eliminated.
*	Digit Removal: Numerical digits are stripped from the text.
*	Currency Symbol Removal: Currency symbols and associated digits are removed from the text.
*	Date Format Removal: Date formats are excluded from the text.
*	Non-ASCII Character Removal: Non-ASCII characters are filtered out from the text.
*	Punctuation Removal: Punctuation marks are removed to enhance text clarity.
*	Word Replacement for Consecutive Letters: Words with multiple consecutive letters are replaced with their standard forms.
*	Inserting Spaces Before Capital Letters: Spaces are inserted before capital letters in the middle of sentences.
*	Stop Word Removal: Common English stop words are eliminated from the text if the rm_stop parameter is set.
*	Lemmatization or Stemming: Depending on the specified method ('L' for lemmatization or 'S' for stemming), the function performs either lemmatization or stemming on the words in the text.
*	Removal of Short Words: Words with a length of less than 4 characters are removed from the text.
