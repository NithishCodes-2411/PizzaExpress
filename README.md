
## Getting Started

1. **Clone or Download the Repository**

2. **Open in Browser**
   - Open `pages/index.html` in your web browser to start using the app.

3. **Admin Access**
   - Go to `pages/admin.html`
   - Enter the secret key: `superadmin123` (can be changed in the code)

## Usage

- **Register:** Create a new account via the Register page.
- **Login:** Log in to access ordering and history features.
- **Order Pizza:** Browse the menu, customize pizzas, add to cart, and checkout.
- **Apply Coupon:** Use code `STUDENT40` for 40% off.
- **View History:** See all your past orders and repeat them.
- **Admin:** Add, edit, or delete menu items.

## Data Storage

- All user, cart, and order data are stored in the browser's `localStorage`.
- Menu data is loaded from `data/menu.json` on first use, then managed via the admin portal.

## Dependencies

- [Bootstrap 5](https://getbootstrap.com/) (CDN)

## Getting Started

1. **Clone or Download the Repository**

2. **Serve the Project**
   - Use a local web server to serve the `pages` directory.  
     For example, in the project root, run:
     ```
     cd pages
     python3 -m http.server 8000
     ```
   - Open your browser and go to `http://localhost:8000/login.html` or `http://localhost:8000/register.html` to get started.

3. **Create an Account**
   - Register a new user or log in with existing credentials to begin using the app.

---

**Enjoy your pizza! 🍕**