# passwordGenerator
Site is live at https://rohi2003.github.io/passwordGenerator/
📸 Screenshots
<img width="960" alt="image" src="https://github.com/Rohi2003/passwordGenerator/assets/87049122/7a41b6fa-5960-4680-9763-49ab3339408e">

User Interface Elements:

inputSlider: Represents an input element for selecting the password length.
lengthDisplay: Displays the current password length selected by the user.
passwordDisplay: Displays the generated password.
copyBtn: Button to copy the generated password to the clipboard.
copyMsg: Message element to indicate whether the password copy was successful or failed.
Checkboxes (uppercaseCheck, lowercaseCheck, numbersCheck, symbolsCheck): Allow the user to choose which types of characters to include in the password.
indicator: Represents a visual indicator of password strength.
generateBtn: Button to trigger the password generation process.
Variables:

password: Stores the generated password.
passwordLength: Represents the length of the password (default value is 10).
checkCount: Tracks the number of checkbox options selected by the user.
Functions:

handleSlider: Updates the UI elements when the password length slider is adjusted.
setIndicator: Sets the visual indicator color based on password strength.
getRndInteger: Generates a random integer within a specified range.
Functions (generateRandomNumber, generateLowerCase, generateUpperCase, generateSymbol): Generate random characters based on user preferences.
calcStrength: Calculates and sets the password strength indicator based on selected options.
copyContent: Copies the generated password to the clipboard and displays a message indicating success or failure.
shufflePassword: Shuffles the characters of the generated password for added security.
handleCheckBoxChange: Handles changes in checkbox states and updates the checkCount variable accordingly.
Event Listeners:

Listens for changes in checkbox states to update the checkCount.
Listens for changes in the password length slider to update the passwordLength.
Listens for clicks on the copy button to trigger the password copy function.
Listens for clicks on the generate button to initiate the password generation process.
Password Generation Logic:

Uses an array (funcArr) to store functions corresponding to selected character types.
Generates a password by concatenating characters based on selected options and ensuring at least one character from each selected type.
Shuffles the generated password for added security.
UI Updates:

Updates the password display in the UI.
Calculates and displays the password strength indicator.
Clipboard Interaction:

Uses the Clipboard API to copy the generated password to the clipboard.
Error Handling:

Handles errors during the copy operation and displays a corresponding message.
User Interaction:

Provides visual feedback to the user when copying the password or adjusting settings.
Randomization:

Uses randomization functions to introduce variability in password generation.
