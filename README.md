# Aoi_Challange
phone keypad C# Coding Challenge for Aoi
Developer: Binyamin Sulaim Jasim
Date: 25-07-2024


1)Mapping: The keypadMapping dictionary holds the possible letters for each digit.

2)Convert Method:

Initialization: result (a StringBuilder object) stores the final output. currentKey and currentKeyCount track the current key being processed and the number of times it has been pressed.

Digit Handling: If the current character is a digit, it checks if it is the same as the last digit processed. If yes, it increments the count; otherwise, it processes the previous key and starts a new sequence.

Space Handling: Processes the current key sequence and resets.

Backspace Handling: Removes the last character from result.

Send Handling: Processes the current key sequence and stops further processing.

3)GetChar Method: Determines the correct letter from the keypadMapping based on the key and the count of presses.
