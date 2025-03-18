# Frappe Payments Master

Frappe Payments Master is a custom Frappe Framework application that integrates payments and subscriptions using Stripe. Designed to streamline financial transaction management within Frappe-based applications, this app enables developers and businesses to implement secure and scalable payment solutions by leveraging Stripe as a payment gateway.

## Key Features
- **Stripe Integration**: Connect your Frappe site to Stripe for processing one-time payments and recurring subscriptions.
- **Subscription Management**: Manage subscription plans directly within your Frappe application.
- **Customizable**: Extend and adapt functionality to suit your project's needs.
- **Multi-Currency Support**: Compatible with Stripe's global capabilities.
- **Easy Installation**: Seamlessly integrates into any Frappe v15 environment.

## Why Use Frappe Payments Master?
If you're building a Frappe-based application (like ERPNext or a custom solution) and need a reliable way to handle payments and subscriptions, this app saves you time and effort by providing a ready-to-use integration with Stripe, one of the most popular and robust payment platforms available.

## Contributions
Contributions are welcome! This project is open-source, and we’re excited to collaborate with the community. If you have ideas for new features, improvements, or bug fixes, feel free to:
- Open an **Issue** to report problems or suggest enhancements.
- Submit a **Pull Request** with your changes.

## Installation

Follow these steps to install and configure Frappe Payments Master in your Frappe environment.

### Prerequisites
- Frappe Framework version 15 installed.
- A configured Bench environment.
- A Stripe account with API keys (public and secret).
- Git installed on your system.

### Installation Steps

1. Navigate to your Bench directory: cd /path/to/your/frappe-bench
2. Get the app from GitHub: bench get-app https://github.com/kamikazce/Frappe-Stripe-Payments-and-Suscriptions.git
3. Activate the virtual environment: source env/bin/activate
4. Install dependencies from requirements.txt: pip install -r apps/frappe_payments_master/requirements.txt
5. Install the app on your site (replace `site_name` with your site, e.g., `testsite`): bench --site site_name install-app frappe_payments_master

### Verification
- Access your site at http://site_name:8000.
- Log in as an administrator and verify that the payment modules are available.

## Usage
(Coming soon: examples of how to create a payment or subscription from code or the UI.)

## License
This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute it according to the license terms.

---

**Thank you for using Frappe Payments Master!**