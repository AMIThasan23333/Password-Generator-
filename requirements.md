# Task requirements

1. It should generate a 8 Character password on first render (landing).
2. User should be able to include or exclude numbers and special character.
3. Alphabetic characters are mandatory. User should not be able to exclude these.
4. After clicking on "Copy to clipboard" the generated password will be copied to clipboard.
5. A alert should appear after clicking on "Copy to clipboard" informing that the action was successful
6. Regenerate button should be able to regenerate a new password with the same given length.
7. User can toggle between raw text and hidden text in password section.


problem 

giving class in html accessing it usuing id 

accesing getElement("char-count"),  not accessing  getElement("char-count").innerText

charCount  is already a number do not have to use charCount.length


  passwordEl.innerText = password; should be   passwordEl.value bcz this is an input element 

  using setAttribute instead of AddAttribute







