Describe: pigLatin()
<!-- vowels -->
Describe findVowels()

Test: "It ignores non-alphabetical characters since they can't be letters."
Code: findVowels("17")
Expected Output: false

Test: "It will turn all characters to lower case."
Code: findVowels("A")
Expected Output: "a"

Test: "It will recognize a vowel at the start of a word"
Code: findVowels("Open door")
Expected Output: "open"

Test: "It will add 'way' to the end of words that begin with a vowel."

<!--Code: pigLatin("a");
Expected Output: "away"

<!-- Describe -->
Describe findConsonant()

Test: "It will recognize a consonant"

Test: "It will recognize a consonant at the start of a word"

Test: "It will move the consonant to the end of the word"

Test: "It will recognize the consonant at the start of the new word"

Test: "It will move the second consonant to the end of the new word"

Test: "It will add 'ay' to the end of the word"

<!-- QU -->
Describe findQU()

Test: "It will recognize QU at the start of a word"

Test: "It will move the QU to the end of the word"

Test: "It will work properly with the second consonant function"


 