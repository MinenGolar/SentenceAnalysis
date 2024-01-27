Sentence Analysis Algorithm
Overview
This pseudocode represents a simple algorithm to analyze a sentence, calculating the length of the sentence, the number of words, and the number of vowels.

Usage
Input: This algorithm reads a sentence character by character until a period is encountered.

Output:

Length of the sentence.
Number of words (assuming words are separated by a single space).
Number of vowels.
Pseudocode
plaintext
Copy code
# sentence_analysis.algo

# Initialize counters
lengthCounter := 0
wordCounter := 0
vowelCounter := 0

# Read input sentence character by character until encountering '.'
WHILE (currentCharacter != '.'):
    # Read the next character
    currentCharacter := ReadNextCharacter()

    # If the current character is not a space, increment lengthCounter
    IF (currentCharacter != ' '):
        lengthCounter := lengthCounter + 1

    # If the current character is a space, increment wordCounter
    IF (currentCharacter == ' '):
        wordCounter := wordCounter + 1

    # If the current character is a vowel, increment vowelCounter
    IF (IsVowel(currentCharacter)):
        vowelCounter := vowelCounter + 1

# Print results
Write("Length of the sentence: ", lengthCounter)
Write("Number of words: ", wordCounter + 1)
Write("Number of vowels: ", vowelCounter)
How to Run
This pseudocode is not executable as is, but you can adapt it to a specific programming language. Consider using Python, JavaScript, or any language of your choice.

Contribution
Feel free to contribute or suggest improvements by creating a pull request.
