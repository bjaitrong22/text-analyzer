Describe: wordCounter()

Test: "It Should return 1 if a passage has just one word."
Code:
const text = "hello";
wordCounter(text);
Expected Output: 1

Test: "It should return 2 if a passage has two words."
code:
const text = "Hello there";
wordCounter(text);
Expected Output: 2

Test: "It should return 0 for an empty string."
Code: wordCounter("");
Expected Output: 0

Test : "It should return 0 for a string that is only spaces."
Code: wordCounter("                   ")
Expected Output: 0

Test: "It should not count numbers as words."
Code:WordCounter("hi there 77 19");
Expected Output: 2

Describe: numberOfOccurrencesInText()
Test:"It should return 0 occurrences of a word for an empty string."
Code:
Const text = "";
Const word = "red"
numberOfOccurrencesInText(word,text);
Expected Output: 0

Test: "It should reeturn 0 occurences of a word when the word and the text are different."
Code:
const text = "red";
const word = "blue";
numberOfOccurrencesInText(word,text);
Expected Output: 0

Test: "It should return the number of occurences of a word."
Code:
Const text = "red blue red red red green";
const word = "red";
numberOfOccurrencesInText(word,text);
Expected Output: 4

Test: "It should return a word match regardless of case."
Code:
Const text = "red RED Red green Green GREEN";
const word = "Red";
numberOfOccurrencesInText(word,text);
Expected Output: 3

Test: "It should return a word match regardless of punctuation."
Code:
Const text = "Red! Red. I like red, green, and yellow.";
const word = "Red";
numberOfOccurrencesInText(word,text);
Expected Output: 3


