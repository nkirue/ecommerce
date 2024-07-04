Webstack - Portfolio Project

# IT Shop eCommerce Website

## Overview
This project is a specialized eCommerce platform developed using the Django framework. It caters to the needs of an IT shop, offering hardware, software, and services. The platform includes features such as user and guest checkout, cart management, and payment integration.

## Table of Contents
- [Overview](#overview)
- [Technologies Used](#technologies-used)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Development Workflow](#development-workflow)
- [Successes](#successes)
- [Challenges](#challenges)
- [Areas for Improvement](#areas-for-improvement)
- [Lessons Learned](#lessons-learned)
- [Next Steps](#next-steps)
- [Contributing](#contributing)
- [License](#license)

## Technologies Used
- **Backend:** Django framework (Python-based web framework)
- **Frontend:** HTML, CSS, JavaScript
- **Payment Integration:** Paypal

## Features
- User authentication and management
- Product catalog with real data rendering
- Shopping cart for registered users
- Guest checkout functionality using cookies
- Payment processing via PayPal

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/it-shop-ecommerce.git
    cd it-shop-ecommerce
    ```
2. Create and activate a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Run migrations:
    ```bash
    python manage.py migrate
    ```
5. Start the development server:
    ```bash
    python manage.py runserver
    ```

## Usage
- Access the website at `http://127.0.0.1:8000/`.
- Register a new account or log in as an existing user.
- Browse the product catalog and add items to the cart.
- Proceed to checkout as a registered user or as a guest.
- Complete the purchase using PayPal.

## Development Workflow
1. **Project Setup & Templates:**  
    - Set up the Django app and initial templates.

2. **Data Structure:**  
    - Define models and render real data on pages.

3. **Site Functionality:**  
    - Implement cart and order functionality for registered users.

4. **Guest Checkout:**  
    - Integrate guest checkout using cookies.

5. **Payment Integration:**  
    - Add PayPal payment integration at checkout.

## Successes
- Developed a fully functional IT shop eCommerce website.
- Successfully implemented both user and guest checkout capabilities.

## Challenges
- Integrating guest checkout functionality.
- Ensuring smooth and secure payment integration.

## Areas for Improvement
- Optimize the user interface for a better user experience.
- Enhance security measures for payment processing.

## Lessons Learned
- Importance of planning data structures in advance.
- Handling different user scenarios (logged in vs guest).

## Next Steps
- Conduct user testing and gather feedback.
- Implement additional features based on user feedback.

## Contributing
Contributions are welcome! Please fork the repository and use a feature branch. Pull requests are warmly welcome.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a pull request

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
