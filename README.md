# Python-Processing-Unordered-Data-Structures
Comment out code for later use.
Highlight lines 5 through 17, which hold your currently active code.
From the menu, select Code→Comment with Line Comment.
Confirm that everything below the docstring is now commented out.
Note: You'll return to this code later. For now, it'll be easier to test your new code by itself.
Take new user input for each word and its frequency.
Position the insertion point at the end of line 3 and press Enter twice.
Starting in line 5, enter the code as shown.


Line 5 prompts the user to enter a list of unique words, to be stored in user_input.
Line 6 prompts the user to enter a corresponding list of word counts, to be stored in user_input2.
Lines 7 and 8 split the user inputs into list variables stored as words and frequency.
Lines 10 through 14 create a dictionary from each input, using the values in words as keys, and the values in frequency as the word count values.
Note: You'll write a more efficient way of adding items to the dictionary later. For now, you'll populate the dictionary manually.

Verify that the dictionary is being populated with your test input.
Run the program.
At the first prompt, type This is a test
At the second prompt, type 3 8 1 4
Note: This group of numbers is arbitrary. You can replace it with any other set of four numbers you want.
Verify that the dictionary prints to the screen, and that each word is a key and each key has its associated value.
Find the number of times the word "test" appears.
Change the print statement on line 15 as shown.
In this print statement, you are accessing the word_count dictionary, providing "test" as the key. The corresponding dictionary value stored under that key (4, if you use the same inputs as before) should be returned by the dictionary in the output.
Run the program using the same inputs you entered before (This is a test and 3 8 1 4).

Verify that your print statement returns the value that was paired with the key "test".
Check if a given word exists in the dictionary.
Click the line number for line 15 to select the whole line, and press Delete to remove the line.
Starting in line 15, write three new statements as shown.


Line 15 prompts the user to identify which word should be checked, assigning it to the variable check_word.
Line 16 assigns a value to the word_exists variable. The value will either be True (if the word to check is in the dictionary) or False (if it is not).
The new print statement in line 17 outputs the result.
Run the program using the same inputs you entered before (This is a test and 3 8 1 4).
When asked to check a word, provide any single word and view the outcome.
Verify that your code returns either True or False, depending on what word you checked.
Close the program console.
