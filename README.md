# Abu Khaled Restaurant Website

## Overview
The Abu Khaled Restaurant Website is a responsive web application showcasing a Middle Eastern restaurant’s menu, specializing in Gulf cuisine. The site provides users with an intuitive interface to explore signature dishes, view detailed product information, manage a shopping cart, learn about the restaurant, and contact the business. Built with HTML and CSS, the website emphasizes a clean, elegant design with a focus on user experience and cultural authenticity.
<img width="1918" height="853" alt="image" src="https://github.com/user-attachments/assets/0d751cf7-a3e8-4137-b503-3dde01112268" />

## Features
- **Homepage (`index.html`)**: Displays a hero banner with a call-to-action to explore the menu and showcases signature dishes with images, prices, and links to detailed pages.
- **Menu Page (`products.html`)**: Lists all available food items (main dishes, sides, and desserts) with images, prices, and links to individual product details.
- **Product Details Pages (`ProductsDetails1.html` to `ProductsDetails8.html`)**: Provide in-depth information about each dish, including a main image, thumbnail gallery, detailed description, price, and an "Add to Cart" button.
- **About Page (`about.html`)**: Shares the restaurant’s story, emphasizing its dedication to Gulf culinary traditions.
- **Cart Page (`cart.html`)**: Displays selected items with product details, quantities, totals, and a checkout option (static implementation; requires JavaScript for full functionality).
- **Contact Page (`contact.html`)**: Offers a form for users to send inquiries (static; requires backend integration for submission).
- **Responsive Design**: Adapts to various screen sizes, ensuring accessibility on desktops, tablets, and mobile devices.
- **Consistent Styling**: Uses a cohesive color scheme (sandy beige, deep red, gold accents) and Arabic-inspired typography (`Amiri` font) to reflect Gulf heritage.

## Project Structure
```
abu-khaled-restaurant/
├── assets/
│   ├── Chicken-Kabsa.jpg
│   ├── Chicken-Kabsa2.jpg
│   ├── Chicken-Kabsa3.jpg
│   ├── Chicken-Kabsa4.webp
│   ├── Lamb-Mandi.jpeg
│   ├── Grilled-Kebabs.jpg
│   ├── Seafood-Machboos.jpg
│   ├── Fattoush-Salad.jpg
│   ├── Luqaimat-Dessert.jpg
│   ├── Tabbouleh-Salad.jpeg
│   ├── Kunafa-Dessert.webp
│   ├── facebook (1).png
│   ├── whatsapp.png
│   ├── instagram.png
│   ├── gulf-feast.jpg
├── ProductsDetails/
│   ├── ProductsDetails1.html  # Chicken Kabsa
│   ├── ProductsDetails2.html  # Lamb Mandi
│   ├── ProductsDetails3.html  # Grilled Kebabs
│   ├── ProductsDetails4.html  # Seafood Machboos
│   ├── ProductsDetails5.html  # Fattoush Salad
│   ├── ProductsDetails6.html  # Luqaimat Dessert
│   ├── ProductsDetails7.html  # Tabbouleh Salad
│   ├── ProductsDetails8.html  # Kunafa Dessert
├── styles.css
├── index.html
├── products.html
├── about.html
├── cart.html
├── contact.html
└── README.md
```

## Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/abu-khaled-restaurant.git
   ```
2. **Navigate to the Project Directory**:
   ```bash
   cd abu-khaled-restaurant
   ```
3. **Serve the Website**:
   - Use a local development server (e.g., Python’s `http.server`):
     ```bash
     python -m http.server 8000
     ```
   - Open a browser and navigate to `http://localhost:8000`.
   - Alternatively, open `index.html` directly in a browser for static viewing (note: some features like relative paths may require a server).

4. **Dependencies**:
   - No external libraries are required for core functionality.
   - The site uses Google Fonts (`Roboto` and `Amiri`) loaded via CDN:
     ```html
     <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&family=Amiri:wght@700&display=swap" rel="stylesheet">
     ```

## Usage
- **Homepage**: Click “Explore Menu” to navigate to the menu page or select a signature dish to view details.
- **Menu Page**: Browse all dishes and click “View Details” to access individual product pages.
- **Product Details**: View detailed descriptions, prices, and images. The thumbnail gallery is static (requires JavaScript for interactivity).
- **Cart Page**: View selected items (static data; requires JavaScript for dynamic updates).
- **Contact Page**: Fill out the contact form (static; requires backend integration for form submission).
- **Navigation**: Use the top navigation bar to switch between pages.

## Food Items
The menu features 8 dishes, each with a dedicated details page:
1. **Chicken Kabsa ($25)**: A Saudi Arabian classic with spiced basmati rice, tender chicken, caramelized onions, raisins, and almonds, served with spicy tomato sauce.
2. **Lamb Mandi ($30)**: Slow-cooked Yemeni lamb with fragrant rice, served with cucumber-yogurt sauce.
3. **Grilled Kebabs ($22)**: Marinated beef and chicken skewers, grilled and served with garlic-tahini sauce.
4. **Seafood Machboos ($28)**: Bahraini seafood medley with spiced rice, garnished with cilantro and tamarind chutney.
5. **Fattoush Salad ($10)**: Levantine salad with crisp vegetables, toasted pita, and sumac-lemon dressing.
6. **Luqaimat Dessert ($12)**: Emirati fried dough balls drizzled with date syrup and sesame seeds.
7. **Tabbouleh Salad ($9)**: Lebanese parsley and bulgur salad with lemon-olive oil dressing.
8. **Kunafa Dessert ($15)**: Layered pastry with creamy cheese, soaked in rosewater syrup, topped with pistachios.

## Styling
- **Color Scheme**:
  - Background: Sandy beige (`#f8e1c7`) for a warm, desert-inspired aesthetic.
  - Accents: Deep red (`#8b1e3f`) and gold (`#d4a017`) for cultural resonance.
  - Text: Dark brown (`#3c2f2f`) for readability.
- **Typography**:
  - `Roboto`: Clean, modern sans-serif for body text.
  - `Amiri`: Arabic-inspired serif for headings, reflecting Gulf heritage.
- **Responsive Design**:
  - Uses CSS Grid for the menu (4 columns on large screens, 3 on medium, 2 on small, 1 on very small).
  - Flexbox for product details and header layout.
  - Media queries ensure mobile-friendly navigation and layouts.

## Future Enhancements
- **JavaScript Interactivity**:
  - Implement dynamic cart functionality (add/remove items, update quantities, calculate totals).
  - Enable thumbnail gallery switching on product details pages.
- **Backend Integration**:
  - Add form submission for the contact page (e.g., using Node.js or PHP).
  - Implement a checkout system with payment processing.
- **Additional Assets**:
  - Add more thumbnail images for each product (currently only Chicken Kabsa includes thumbnails).
- **SEO Optimization**:
  - Add meta tags for better search engine visibility.
- **Accessibility**:
  - Improve ARIA attributes for screen readers.
  - Ensure keyboard navigation support.

## Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make changes and commit (`git commit -m "Add your feature"`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For inquiries, contact the Abu Khaled team via the [Contact Page](contact.html) or email [support@abukhaled.com](mailto:support@abukhaled.com).
