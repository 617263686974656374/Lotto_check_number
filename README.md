# Lotto_check_number
This Java application designed to collect and process a series of unique user-inputted numbers within a specified range.
This application primarily functions as a lottery number picker, where the user is required to input six unique numbers between 1 and 45. The program ensures all inputs are within the allowed range and checks for duplicate entries.

#### Features
- **User Input Validation**: The program validates that all entered numbers are integers and within the range of 1 to 45.
- **Duplicate Detection**: It checks for and notifies the user of any duplicate entries, prompting for a re-entry until a unique number is provided.
- **Sorting**: Upon successful entry of all six numbers, the program sorts them in ascending order to facilitate easier viewing and analysis.
- **Error Handling**: Implements robust error handling to manage non-integer inputs and out-of-range entries effectively.

#### Usage Instructions
- When prompted, enter a number between 1 and 45.
- If a non-integer or an out-of-range number is entered, an error message will appear, and you will be asked to re-enter a valid number.
- If a duplicate number is entered, a notification will be displayed, and you will need to enter a different number.
