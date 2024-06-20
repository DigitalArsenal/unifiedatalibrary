# Unified Data Library - Credential Phishing Demo

This repository contains a demo page designed to illustrate how easy it is to phish credentials. The page mimics a login prompt for `unifieddatalibrary.com` and is part of a defensive cyber demonstration on behalf of the SDA Tap Lab.

## Contents

- `index.html`: The main HTML file for the demo page.
- `README.md`: This file.

## Description

The demo page simulates a phishing attack by prompting users to enter their credentials (username and password). **Important:** The credentials are not stored or transmitted anywhere; they are only displayed in an alert box within the browser for demonstration purposes. 

## Usage

To use the demo page, follow these steps:

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/yourusername/unifieddatalibrary-phishing-demo.git
    ```

2. Navigate to the cloned repository:
    ```bash
    cd unifieddatalibrary-phishing-demo
    ```

3. Open the `index.html` file in your web browser to view the demo page.

## Files

### `index.html`

This file contains the HTML and JavaScript code for the demo page. The page includes:

- A custom login prompt that mimics the appearance of a real login form.
- A script that displays the entered credentials (partially masked) in an alert box.
- Links to resources for learning more about phishing.

## Security Note

The credentials entered into the demo page are only displayed within an alert box and never leave the browser. This ensures that no sensitive information is transmitted or stored.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
