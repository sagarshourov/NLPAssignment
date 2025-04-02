Course Code: 0714 02 CSE 5127, Course Title: Statistical Natural Language Processing
Assignment due date: April 05 2025, 11:59 pm
Submission: Sending to the email ‘rafizul@cse.ku.ac.bd’
Write regular expressions to perform the following tasks (problem 1 – problem 9):
1. Extract all email addresses from a given text. Assume that email addresses follow the pattern
‘username@domain.com’.
2. Match all valid phone numbers in the format ‘(XXX) XXX-XXXX’, where `X` is a digit.
3. Find all words that start with a capital letter and are followed by lowercase letters (e.g., "Hello",
"Nlp").
4. Extract all hashtags (e.g., ‘#NLP’, ‘#MachineLearning’) from a text.
5. Extract all URLs from a text. Assume URLs start with ‘http://’ or ‘https://’ and may contain
alphanumeric characters, hyphens, slashes, and periods.
6. Match dates in the format ‘YYYY-MM-DD’. Ensure that the month is between 01 and 12, and the day
is between 01 and 31.
7. Remove all punctuation marks from a given text, except for apostrophes in contractions (e.g., "don't"
should remain unchanged).
8. Extract all words that contain at least two vowels (a, e, i, o, u) in a row (e.g., "queue", "ai").
9. Find the set of all strings with two consecutive repeated words (e.g., “Humbert
Humbert” and “the the” but not “the bug” or “the big bug”);
10. Write a Python script that uses regular expressions to perform the following tasks:
i. Tokenize a sentence into words, ignoring punctuation marks.
ii. Normalize text by converting it to lowercase and removing extra spaces.
iii. Extract all named entities that start with a capital letter and are at least two characters long (e.g.,
"John", "New York").
iv. Replace all occurrences of "e.g." and "i.e." with "for example" and "that is", respectively.
11. Show the results, in a table, of applying the Minimum Edit Distance algorithm to the distance between
“kitten” and “sitting” using Levenshtein distance with cost of 1 for insertions or deletions, 2 for
substitutions.
Hint: Section 2.8.1 of the textbook “Speech and Language Processing” by Daniel Jurafsky.
12. Compute the t value of new companies for a corpus with the following counts:
C(new) = 30, 000, C(companies) = 9, 000, C(new companies) = 20, and corpus
size N = 15, 000, 000
