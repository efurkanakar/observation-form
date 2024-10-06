# Observation Report Form

This is a simple web-based observation report form that allows astronomers to submit their observation details. The form dynamically updates fields for star observation details and uses EmailJS to send the report.

## Features

- **Date Picker**: Automatically sets the current date.
- **Observation Status**: Option to select if the observation was carried out (Yes/No).
- **Dynamic Star Fields**: Ability to add or remove multiple star observation entries.
- **Form Submission**: Sends the form data via EmailJS after submission.
- **BCC Option**: Allows users to send a BCC copy of the form to another email.

## How to Use

1. Clone this repository:
    ```bash
    git clone https://github.com/efurkanakar/observation-form.git
    ```

2. Open the `index.html` file in any web browser to access the form.

3. To set up EmailJS:
    - Obtain your EmailJS public key.
    - Update the `emailjs.init()` method with your EmailJS public key in the JavaScript part of the code.
    - Set up EmailJS templates for your observation report in the EmailJS dashboard.

## License

This project is licensed under the MIT License. Feel free to modify and use it as needed.

## Contact

For any issues, suggestions, or feedback, feel free to reach out to me at my email address.
