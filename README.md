# 🍳 CookiePuky – AI-Powered Recipe Generator

CookiePuky is a smart, mobile-first web app that turns your available ingredients into delicious Indian recipes. Enter what you have, and let AI suggest the perfect dishes — with instant grocery links for anything you're missing.

## ✨ Features

- **AI Recipe Generation** – Get recipe suggestions ranked by ingredient match percentage
- **Tag-Based Ingredient Input** – Add ingredients easily with comma-separated tags
- **Grocery Integration** – One-click links to Blinkit, Zepto & Swiggy Instamart for missing ingredients
- **Smart Filters** – Filter by Veg/Non-Veg, Quick (<30 min), Easy, and more
- **Premium Variations** – Unlock multiple styles of the same dish (Hyderabadi, Kolkata, Mughlai, etc.)
- **Responsive Design** – Mobile-first, card-based UI with smooth animations

## 📄 Pages

| Page | Description |
|------|-------------|
| **Home** | Landing page with hero section, feature highlights, and CTA |
| **Recipes** | Core feature — enter ingredients, generate & browse recipes |
| **Ingredients** | Browse common ingredients with category filters |
| **Pricing** | Premium plan details (₹49/month) |
| **Services** | Overview of app capabilities |
| **FAQs** | Frequently asked questions |

## 🛠 Tech Stack

- **React 18** with TypeScript
- **Vite** for fast development & builds
- **Tailwind CSS** with custom design tokens
- **shadcn/ui** component library
- **React Router** for client-side routing
- **TanStack React Query** for data fetching
- **Lucide React** for icons

## 🚀 Getting Started

```bash
# Clone the repository
git clone <YOUR_GIT_URL>

# Navigate to the project
cd cookiepuky

# Install dependencies
npm install

# Start the development server
npm run dev
```

The app will be available at `http://localhost:8080`.

## 📁 Project Structure

```
src/
├── components/
│   ├── ui/              # shadcn/ui components
│   ├── Navbar.tsx        # Fixed navigation bar
│   ├── Footer.tsx        # Site footer
│   ├── IngredientInput.tsx  # Tag-based ingredient entry
│   ├── RecipeCard.tsx    # Recipe display card with grocery links
│   └── NavLink.tsx       # Navigation link component
├── pages/
│   ├── Index.tsx         # Home / Landing page
│   ├── Recipes.tsx       # AI recipe generator
│   ├── Ingredients.tsx   # Ingredient browser
│   ├── Pricing.tsx       # Premium pricing
│   ├── Services.tsx      # Services overview
│   ├── FAQs.tsx          # FAQ section
│   └── NotFound.tsx      # 404 page
├── hooks/                # Custom React hooks
├── lib/                  # Utility functions
└── index.css             # Design system & CSS variables
```

## 💰 Monetization

| | Free | Premium (₹49/mo) |
|---|---|---|
| Recipes per search | Limited | Unlimited |
| Variations per dish | 1 | Up to 5 |
| Grocery links | ❌ | ✅ |
| Ads | Yes | No |

## 🔮 Future Enhancements

- Real AI-powered recipe generation via backend API
- User authentication & saved recipes
- Voice-based ingredient input
- Camera-based ingredient detection
- Daily meal planner
- Budget-based recipe suggestions
- Grocery price comparison

## 📜 License

This project is private and built with [Lovable](https://lovable.dev).
