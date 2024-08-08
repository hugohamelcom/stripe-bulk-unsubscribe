# Stripe Bulk Unsubscribe

## Overview

This project provides a simple web interface to bulk unsubscribe customers from Stripe subscriptions. It is designed to help manage and cancel multiple subscriptions efficiently.

## Features

- **API Key Validation**: Ensures that the provided Stripe API key has the necessary permissions.
- **Product Selection**: Allows users to select products for which they want to fetch subscribers.
- **Subscriber Management**: Enables users to select and bulk unsubscribe subscribers from the selected products.

## Usage

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/stripe-bulk-unsubscribe.git
    cd stripe-bulk-unsubscribe
    ```

2. **Open `index.html`**:
    Open the `index.html` file in your preferred web browser.

3. **Enter Stripe API Key**:
    - Input your Stripe API key in the provided field.
    - Click on the "Validate Key" button to ensure the key has the necessary permissions.

4. **Select Products**:
    - Once the API key is validated, the product selection section will be displayed.
    - Click on "Select All" to select all products or choose specific products from the list.
    - Click on "Fetch Subscribers" to retrieve the list of subscribers for the selected products.

5. **Manage Subscribers**:
    - The subscribers section will be displayed with the list of subscribers.
    - Click on "Select All" to select all subscribers or choose specific subscribers from the list.
    - Click on "Cancel Subscriptions" to bulk unsubscribe the selected subscribers.

## File Structure

- `index.html`: The main HTML file containing the structure and layout of the web interface.
- `script.js`: The JavaScript file containing the logic for API key validation, product fetching, and subscriber management.
- `README.md`: This file, providing an overview and usage instructions for the project.

## Dependencies

- **Tailwind CSS**: Used for styling the web interface. It is included via CDN in the `index.html` file.

## Notes

- Ensure that your Stripe API key has the following permissions:
  - Products (Read)
  - Prices (Read)
  - Customer (Read)
  - Subscriptions (Write)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## Acknowledgements

- [Stripe API](https://stripe.com/docs/api) for providing the necessary endpoints to manage subscriptions.
- [Tailwind CSS](https://tailwindcss.com/) for the styling framework.

Feel free to customize this README to better fit your project's needs.
