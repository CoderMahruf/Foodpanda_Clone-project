# Foodpanda Clone Project

This is a Django-based web application that replicates some of the core features of Foodpanda, a popular food and grocery delivery platform. The project provides a user-friendly interface to browse menus, order food, and book tables at restaurants.

## Features

### 1. Homepage
- **Food & Grocery Delivery Section**: Highlights the service offering with a visually appealing banner.
- **Call-to-Action Button**: An "Order Now" button for quick access to the menu.

### 2. Discounts Section
- Displays promotional offers such as:
  - **Tasty Thursdays**: 20% off.
  - **Pizza Days**: 15% off.

### 3. Menu
- Filter options to view food categories like Pizza, Burger, Pasta, Fries, and Sandwiches.
- Individual cards for each food item with:
  - Name.
  - Description.
  - Price.
  - "Add to Cart" button.

### 4. Book a Table
- Form to input details:
  - Name, Phone Number, Email.
  - Number of persons.
  - Date of booking.
- Embedded Google Maps for location reference (currently showing an error, needs fixing).

### 5. Admin Login
- Secure login interface for admins to manage the content and orders.

## Prerequisites

Before running the project, ensure you have the following installed:
- Python 3.8+
- Django 4.0+
- SQLite (default database for Django)
- A modern web browser

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-repository-url/foodpanda-clone.git
   cd foodpanda-clone
   ```

2. **Create a Virtual Environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Apply Migrations**:
   ```bash
   python manage.py migrate
   ```

5. **Run the Development Server**:
   ```bash
   python manage.py runserver
   ```

6. Open your browser and navigate to `http://127.0.0.1:8000` to view the application.

## Usage

- Navigate through the homepage to explore features.
- Use the "Menu" section to view and order food items.
- Use the "Book a Table" section to make reservations.

## Known Issues

1. **Google Maps Integration**:
   - The embedded Google Maps is currently showing an error: "This page can't load Google Maps correctly."
   - Fix: Ensure that you have a valid Google Maps API key and update the settings in the project.

2. **Design Adjustments**:
   - Some UI components might require further refinement for better responsiveness on mobile devices.

## Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bug fix:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes and push to the branch:
   ```bash
   git push origin feature-name
   ```
4. Create a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments

- [Django Documentation](https://docs.djangoproject.com/)
- [Foodpanda](https://www.foodpanda.com/) for design inspiration.

---

Feel free to customize the README file as per your specific project requirements.

