# AGS E-Commerce Platform

AGS is a simple e-commerce web application for managing products, clients, and orders. It features both a public-facing shopping interface and an admin dashboard for product and user management.

## Features

- User registration and login
- Product browsing and cart management
- Checkout and invoice generation
- Admin dashboard for managing products, users, and requests
- Responsive design

## Project Structure

```
ags_db.sql
AGS/
  app.js
  index.php
  public.php
  checkout.html
  ...
  Admin/
    dashboard.php
    users.php
    products.php
    requests.php
    main.js
    ...
  Public/
    public.php
    invoice.php
    JS/
      app.js
    Css/
      styles.css
      style.css
```

## Getting Started

### Prerequisites

- PHP >= 7.x
- MySQL/MariaDB
- Web server (e.g., Apache)
- Node.js (optional, for frontend tooling)

### Installation

1. **Clone the repository:**
   ```
   git clone <your-repo-url>
   ```

2. **Database Setup:**
   - Import `ags_db.sql` into your MySQL database.
   - Update database credentials in `AGS/config.php` and `AGS/Public/config.php`.

3. **Run the Application:**
   - Place the `AGS` folder in your web server's root directory.
   - Access the app via `http://localhost/AGS/index.php`.

### Admin Access

- Go to `http://localhost/AGS/Admin/index.php`
- Login with an admin account (see the `clients` table in the database for admin users).

## Usage

- **Public Area:** Users can register, log in, browse products, add to cart, and checkout.
- **Admin Area:** Admins can manage products, users, and view requests/orders.

## Customization

- **Styling:** Modify CSS files in `AGS/Public/Css/` and `AGS/Admin/`.
- **Product Images:** Place product images in the appropriate `image/` or `images/` directory.

## License

This project is for educational purposes.

---

**Note:** For any issues or questions, please contact the project maintainer.
