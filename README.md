# Dreamsunflower Cake Shop 🧁

A beautiful, modern website for Dreamsunflower artisan cake shop built with React, featuring online ordering, user authentication, and a complete e-commerce experience.

## Features ✨

### 🏠 Home Page
- Beautiful hero section with call-to-action
- Featured cake catalog with high-quality images
- Add to cart functionality
- Favorite/wishlist features
- Responsive design for all devices

### 🛒 Shopping & Ordering
- **Shopping Cart**: Add, remove, and update quantities
- **Checkout Process**: Complete order form with delivery options
- **Order Confirmation**: Professional order confirmation system
- **Free Delivery**: Free shipping for orders over $75

### 👤 User Authentication
- **Login System**: Secure user authentication
- **User Registration**: Complete signup process with validation
- **Demo Account**: Pre-configured demo user for testing

### 📞 Contact & Information
- **Contact Page**: Contact form, business information, and FAQ
- **Owners Page**: Meet the team, company story, and values
- **Business Hours**: Complete contact information and hours

### 🎨 Design Features
- Modern, elegant design with custom color scheme
- Responsive layout for mobile, tablet, and desktop
- Smooth animations and transitions
- Professional typography with Google Fonts
- Tailwind CSS for consistent styling

## Demo Credentials 🔑

To test the application, use these demo login credentials:

```
Email: demo@dreamsunflower.com
Password: demo123
```

## Quick Start 🚀

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn

### Installation

1. **Clone or download the project files**

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   - Navigate to `http://localhost:5173`
   - The website will automatically reload when you make changes

## Available Scripts 📝

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## Technology Stack 🛠️

- **Frontend Framework**: React 18
- **Build Tool**: Vite
- **Styling**: Tailwind CSS
- **Routing**: React Router DOM
- **Icons**: Lucide React
- **State Management**: React Context API
- **Storage**: localStorage (for demo purposes)

## Project Structure 📁

```
src/
├── components/
│   └── Layout.jsx          # Main layout with navigation
├── contexts/
│   ├── AuthContext.jsx     # User authentication
│   └── CartContext.jsx     # Shopping cart management
├── pages/
│   ├── Home.jsx           # Homepage with cake catalog
│   ├── Login.jsx          # User login
│   ├── Register.jsx       # User registration
│   ├── Cart.jsx           # Shopping cart
│   ├── Checkout.jsx       # Order checkout
│   ├── Contact.jsx        # Contact information
│   └── Owners.jsx         # About the owners
├── App.jsx                # Main app component
├── main.jsx              # App entry point
└── index.css             # Global styles
```

## Features in Detail 📋

### Shopping Cart
- Persistent cart using localStorage
- Quantity controls with +/- buttons
- Remove items functionality
- Real-time price calculations
- Free delivery threshold tracking

### User Authentication
- Form validation and error handling
- Password visibility toggle
- Remember me functionality
- Automatic demo user creation
- Secure logout functionality

### Order System
- Complete checkout form
- Delivery date and time selection
- Payment information collection
- Order confirmation with tracking number
- Email and SMS notifications (simulated)

### Responsive Design
- Mobile-first approach
- Tablet and desktop optimizations
- Touch-friendly interface
- Accessible navigation
- Print-friendly styles

## Customization 🎨

### Colors
The website uses a custom color palette defined in `tailwind.config.js`:
- Primary: Yellow/Gold theme
- Secondary: Pink/Rose theme
- Neutral: Gray scales

### Fonts
- Headers: Playfair Display (serif)
- Body: Inter (sans-serif)

### Images
Currently using Unsplash images for demonstrations. Replace with actual product photos in production.

## Production Deployment 🌐

### Build for Production
```bash
npm run build
```

### Deploy Options
- **Netlify**: Drag and drop the `dist` folder
- **Vercel**: Connect your Git repository
- **GitHub Pages**: Use the built files
- **Traditional Web Hosting**: Upload `dist` folder contents

### Environment Configuration
For production, consider:
- Replace localStorage with a real database
- Add payment processing (Stripe, PayPal)
- Implement real authentication (Firebase, Auth0)
- Add email services (SendGrid, Mailgun)
- Set up analytics (Google Analytics)

## Browser Support 🌍

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Contributing 🤝

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## Future Enhancements 🔮

- Real payment processing
- User order history
- Email notifications
- Inventory management
- Customer reviews and ratings
- Loyalty program
- Multi-language support
- SEO optimization
- Performance monitoring

## Support 💬

For questions or support:
- Email: hello@dreamsunflower.com
- Phone: (555) 123-4567

## License 📄

This project is created for demonstration purposes. All images are from Unsplash and used under their license terms.

---

**Dreamsunflower Cake Shop** - Where every cake is a masterpiece crafted with love! 🎂✨ 