# Problem Set 2a
 
 
Designing and implementing a program, 'readability', that computes the Coleman-Liau index of the text.

Implementing the program by first prompting the user for a string of text.
The program counts the number of letters, words, and sentences in the text. A letter is considered any lowercase character from a to z
or any uppercase character from A to Z, any sequence of characters separated by spaces also counts as a word,
and any occurrence of a period, exclamation point, or question mark indicates the end of a sentence.

The program prints as output "Grade X" where X is the grade level computed by the Coleman-Liau formula, rounded to the nearest integer.
If the resulting index number is 16 or higher (equivalent to or greater than a senior undergraduate reading level),
the program outputs "Grade 16+" instead of giving the exact index number.
If the index number is less than 1, the program outputs "Before Grade 1".
