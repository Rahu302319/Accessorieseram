# Power BI Report Login Portal

This project provides a simple login interface to access a Power BI report embedded in an HTML page. The project is designed for users to securely log in with a username and password, and upon successful login, the Power BI report will be displayed without the navigation bar.

## Features

- **Login Interface**: Secure login form to authenticate users before accessing the report.
- **Embedded Power BI Report**: Displays the report in a chromeless mode (no navigation bar).
- **Logout Option**: Allows users to log out and return to the login screen.

## Getting Started

### Prerequisites

- Web browser to open and view the HTML page.
- Access to the Power BI report URL.

### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Rahu302319/Acc.git
    ```
2. **Navigate to the project folder**:
    ```bash
    cd Acc
    ```

### Usage

1. Open the HTML file (`index.html`) in a web browser.
2. Enter the username and password to log in (default credentials are encoded in the JavaScript code).
3. If the credentials are correct, the Power BI report will be displayed.

### Project Structure

- `index.html` - Main HTML file with the login form and embedded Power BI report.
- `README.md` - Documentation file.
- `style.css` (optional) - External CSS file for additional styling (if any).

### Customization

- **Username and Password**: Update the encoded values in the `validateLogin` function within `index.html`.
- **Power BI Report URL**: Update the `reportUrl` variable in `index.html` with the new report link if needed.

## License

This project is open source and available under the [MIT License](LICENSE).

## Contributing

Contributions are welcome! Feel free to open a pull request or report any issues.

## Contact

For questions or assistance, please contact the repository owner.
