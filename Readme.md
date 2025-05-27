# FlavorlyFood

A web-based food ordering platform with user and admin interfaces, product management, cart, checkout, and order tracking features.

## Project Structure
FlavorlyFood/ │ ├── about.php # About page ├── cart.php # Shopping cart page ├── category.php # Food category listing ├── checkout.php # Checkout and order placement ├── contact.php # Contact form ├── food_db.sql # Database schema and sample data ├── home.php # Main landing page after login ├── index.html # Public homepage with carousel ├── login.php # User login ├── menu.php # Menu listing all products ├── orders.php # User's order history ├── pizza.css # Custom CSS for pizza-themed pages ├── pizza.js # JS for carousel/banner background ├── profile.php # User profile page ├── quick_view.php # Quick view for product details ├── Readme.md # This file ├── register.php # User registration ├── search.php # Product search page ├── update_address.php # Update user address ├── update_profile.php # Update user profile │ ├── .vscode/ │ └── settings.json # VSCode workspace settings │ ├── ab/ │ └── index.html # Alternate homepage (demo/variant) │ ├── admin/ # Admin dashboard and management │ ├── admin_accounts.php # Manage admin accounts │ ├── admin_login.php # Admin login │ ├── dashboard.php # Admin dashboard │ ├── messages.php # View user messages │ ├── placed_orders.php # Manage placed orders │ ├── products.php # Add/delete products │ ├── register_admin.php # Register new admin │ ├── update_product.php # Update product details │ └── users_accounts.php # Manage user accounts │ ├── components/ # Reusable PHP components │ ├── connect.php # Database connection │ ├── user_header.php # User header/navbar │ ├── admin_header.php # Admin header/navbar │ ├── footer.php # Footer section │ └── add_cart.php # Add to cart logic │ ├── css/ │ ├── style.css # Main site styles │ └── admin_style.css # Admin dashboard styles │ ├── images/ # General images/icons ├── js/ │ ├── script.js # Main JS for UI interactions │ └── admin_script.js # Admin dashboard JS ├── project images/ # Additional project images ├── uploaded_img/ # Uploaded product images

## Features

- **User Side**
  - Browse menu and categories
  - Add products to cart
  - Checkout and place orders
  - View and update profile/address
  - Track order status
  - Search products

- **Admin Side**
  - Manage products (add, update, delete)
  - View and manage orders
  - Manage user and admin accounts
  - View messages from users

## Setup

1. Import `food_db.sql` into your MySQL database.
2. Update database credentials in [`components/connect.php`](components/connect.php).
3. Place the project in your web server's root directory (e.g., `htdocs` for XAMPP).
4. Access via `http://localhost/FlavorlyFood/`.

## Scripts

- [`js/script.js`](js/script.js): Handles UI toggles, loader, and input validation.
- [`js/admin_script.js`](js/admin_script.js): Admin panel UI interactions.
- [`pizza.js`](pizza.js): Carousel/banner background logic for the homepage.

## Styling

- [`css/style.css`](css/style.css): Main user-facing styles.
- [`css/admin_style.css`](css/admin_style.css): Admin dashboard styles.
- [`pizza.css`](pizza.css): Special styles for pizza-themed pages.

## Database

See [`food_db.sql`](food_db.sql) for table structures:
- `users`, `admin`, `products`, `orders`, `cart`, `messages`

## Credits

- Built with PHP, MySQL, HTML, CSS, and JavaScript.
- Uses [Font Awesome](https://fontawesome.com/) and [Materialize CSS](https://materializecss.com/).

---

*For more details, see the source files in each directory.*
