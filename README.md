## Word Frequency Counter using Python and JSON

This Python script analyzes a given text and generates a JSON file containing the frequency count of each word in the text. It then provides a function to search for specific words in the generated frequency count and displays their occurrences.

### How it works

1. The provided text is split into words, and a dictionary is created to store the frequency count of each word.
2. The script processes the text to count the occurrences of each word and stores the counts in the dictionary.
3. The resulting frequency count dictionary is saved in a JSON file named `demo.json`.
4. The `count` function allows users to input words they want to search for in the frequency count.
5. The function loads the frequency count from the JSON file and displays the count of each input word if it exists in the frequency count. If a word is not found, it notifies the user.

### Example Usage

```python
Input >>> count('on', 'dddd', 'sister', 'dedef')
Output >> on 1
          dddd not found
          sister 2
          dedef not found
