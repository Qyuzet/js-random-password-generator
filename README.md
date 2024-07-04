# JS Random Password Generator

## Overview

The **JS Random Password Generator** is a web application designed to create secure, random passwords based on user-defined criteria. Built using JavaScript, HTML, and CSS, this project demonstrates essential front-end development skills and offers a practical tool for generating passwords.

[TRY NOW!](https://qyuzet.github.io/js-random-password-generator/)

## Features

- **Customizable Password Length**: Users can specify the desired length of the password.
- **Character Types**: Options to include or exclude uppercase letters, lowercase letters, numbers, and special characters.
- **Copy to Clipboard**: Easily copy the generated password to the clipboard.

## Installation

To run the app locally:

1. Clone the repository:
    ```bash
    git clone https://github.com/Qyuzet/js-random-password-generator.git
    ```
2. Navigate to the project directory:
    ```bash
    cd js-random-password-generator
    ```
3. Open `index.html` in your preferred web browser.

## File Structure

- **index.html**: The main HTML file containing the structure of the app.
- **style.css**: The CSS file providing the styling for the app.
- **script.js**: The JavaScript file containing the logic and functionality of the app.

## Usage

1. Open `index.html` in a web browser.
2. Specify the desired password length.
3. Select the character types to include.
4. Click "Generate Password" to create a new password.
5. Click the "Copy to Clipboard" button to copy the generated password.

### Code Explanation

#### HTML (`index.html`)

The HTML file sets up the basic structure of the password generator, including input fields for password length, checkboxes for character types, and buttons for generating and copying passwords.

#### CSS (`style.css`)

The CSS file ensures the app has a clean and modern look. It styles the form, buttons, and other UI elements.

#### JavaScript (`script.js`)

The JavaScript file implements the core functionality of the app. Key functions and features include:

- **Event Listeners**: Handling user interactions such as selecting options and clicking buttons.
- **Password Generation**:
  - **generatePassword()**: Creates a random password based on the selected criteria.
  - **getRandomCharacter()**: Retrieves random characters from the specified sets (uppercase, lowercase, numbers, special characters).
- **Clipboard Functionality**:
  - **copyToClipboard()**: Copies the generated password to the clipboard for easy use.

### Detailed Explanation

#### Generating Passwords
The `generatePassword()` function constructs the password by randomly selecting characters from the chosen sets. It ensures that the password length matches the user's input and includes a mix of the specified character types.

#### Copy to Clipboard
The `copyToClipboard()` function allows users to easily copy the generated password. It uses the `navigator.clipboard.writeText` method for this functionality.

## Responsive Design

The app is designed to be fully responsive, ensuring it works seamlessly on various devices, including desktops, tablets, and mobile phones. The use of CSS Flexbox and media queries ensures that the layout adjusts appropriately to different screen sizes.

## Academic Insights

This project demonstrates key concepts in web development, including DOM manipulation, event handling, and random data generation. It serves as a practical example for computer science students to understand how front-end technologies can be integrated to create functional web applications. Through this project, students can learn:

- **HTML5**: Structuring web content.
- **CSS3**: Styling web pages.
- **JavaScript**: Adding interactivity and handling data.
- **Responsive Design**: Ensuring usability across different devices.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/Qyuzet/js-random-password-generator/blob/main/LICENSE) file for details.

## Contact

For any questions or suggestions, please contact Riki Awal Syahputra at [riqyuzet@gmail.com](mailto:riqyuzet@gmail.com).

## Live Demo

You can try the app live at [JS Random Password Generator Demo](https://qyuzet.github.io/js-random-password-generator/).

For more details and to view the code, visit the [GitHub repository](https://github.com/Qyuzet/js-random-password-generator).
