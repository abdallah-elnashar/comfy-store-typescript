# 🛒 Comfy Store

A full-stack e-commerce application built with TypeScript, React, and Redux Toolkit. Comfy Store provides a seamless online shopping experience with modern UI/UX design.

![Comfy Store Banner](./src/assets/hero1.webp)

## 🌟 Features

- ✅ **User Authentication**: Secure login, register, and guest user functionality
- ✅ **Product Catalog**: Browse products with advanced filters, search, and sorting
- ✅ **Shopping Cart**: Real-time cart updates with add, edit, and remove functionality
- ✅ **Theme Toggle**: Switch between dark and light modes
- ✅ **Checkout System**: Complete order placement with shipping information
- ✅ **Order History**: Track all previous orders
- ✅ **Responsive Design**: Optimized for all devices and screen sizes

## 🛠️ Tech Stack

### Frontend
- **TypeScript** - Type-safe JavaScript
- **React.js** - UI library
- **Redux Toolkit** - State management
- **React Router** - Client-side routing
- **Tailwind CSS** - Utility-first CSS framework
- **shadcn/ui** - Re-usable component library
- **Axios** - HTTP client

### Backend
- **Strapi API** - Headless CMS for backend data

## 📸 Screenshots

### Home Page
![Home Page](./screenshots/home.png)

### Products Page
![Products Page](./screenshots/products.png)

### Cart Page
![Cart Page](./screenshots/cart.png)

### Checkout Page
![Checkout Page](./screenshots/checkout.png)

## 🚀 Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone https://github.com/abdallah-elnashar/comfy-store-typescript.git
cd comfy-store-typescript
```

2. Install dependencies
```bash
npm install
```

3. Start the development server
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173`

## 📦 Build for Production

```bash
npm run build
```

## 🔧 Environment Variables

Create a `.env` file in the root directory:

```env
VITE_API_URL=https://strapi-store-server.onrender.com/api
```

## 📚 Project Structure

```
comfy-store-typescript/
├── src/
│   ├── assets/          # Images and static files
│   ├── components/      # Reusable components
│   │   ├── ui/         # shadcn/ui components
│   ├── features/        # Redux slices
│   │   ├── cart/       # Cart state management
│   │   ├── theme/      # Theme state management
│   │   ├── user/       # User state management
│   ├── pages/          # Page components
│   ├── utils/          # Utility functions and types
│   ├── App.tsx         # Main app component
│   ├── store.ts        # Redux store configuration
│   └── main.tsx        # Entry point
├── public/
└── package.json
```

## 🎨 Key Components

### State Management
- **Redux Toolkit** for global state
- **Cart Slice**: Manages shopping cart items and calculations
- **User Slice**: Handles authentication state
- **Theme Slice**: Controls dark/light mode

### Routing
- **React Router v6** for navigation
- Protected routes for authenticated users
- Loaders for data fetching
- Actions for form submissions

### UI Components
- **shadcn/ui**: Pre-built, customizable components
- **Tailwind CSS**: Utility-first styling
- **Lucide Icons**: Modern icon library

## 🔐 Authentication

The app supports three authentication methods:
1. **Register**: Create a new account
2. **Login**: Sign in with credentials
3. **Guest User**: Browse and shop without registration

## 🛍️ Shopping Flow

1. Browse products on the landing page or products page
2. Filter and search for specific items
3. Add products to cart with color and quantity selection
4. Review cart and adjust quantities
5. Proceed to checkout (login required)
6. Place order with shipping information
7. View order history

## 📱 Responsive Design

Comfy Store is fully responsive and optimized for:
- 📱 Mobile devices (320px and up)
- 📱 Tablets (768px and up)
- 💻 Desktops (1024px and up)
- 🖥️ Large screens (1280px and up)

## 🎓 Learning Outcomes

This project helped me master:
- Advanced TypeScript patterns and type safety
- Complex state management with Redux Toolkit
- Building reusable components with proper TypeScript interfaces
- Implementing protected routes and user authentication
- Working with modern React patterns and hooks
- Creating a polished UX with Tailwind and shadcn/ui
- API integration and error handling

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**Abdallah Elnashar**

- LinkedIn: [@abdallah-elnashar-dev](https://www.linkedin.com/in/abdallah-elnashar-dev/)
- GitHub: [@abdallah-elnashar](https://github.com/abdallah-elnashar)

## 🙏 Acknowledgments

- [Udemy - Practical TypeScript Course](https://www.udemy.com/)
- [Strapi Store Server](https://strapi-store-server.onrender.com/api) for the backend API
- [shadcn/ui](https://ui.shadcn.com/) for the amazing component library
- [Tailwind CSS](https://tailwindcss.com/) for the utility-first CSS framework

## 📞 Support

If you have any questions or need help, feel free to reach out or open an issue!

---

⭐ **If you found this project helpful, please give it a star!** ⭐
