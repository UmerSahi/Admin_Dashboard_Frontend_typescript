# StoreFlow - E-commerce Analytics Dashboard

A modern, responsive analytics dashboard built with Next.js, featuring real-time revenue tracking, inventory management, and product registration capabilities.

![StoreFlow Dashboard](https://images.pexels.com/photos/7654905/pexels-photo-7654905.jpeg)

## Features

### Revenue Analysis
- Real-time order and revenue tracking
- Interactive charts with multiple time periods (daily, weekly, monthly, annually)
- Category-based revenue filtering
- Revenue trend visualization
- Growth comparisons with previous periods

### Inventory Management
- Complete product inventory overview
- Advanced sorting and filtering capabilities
- Real-time stock level updates
- Low stock alerts and forecasting
- Product search functionality
- Stock status indicators

### Product Registration
- User-friendly product registration form
- Image upload capability
- Comprehensive product details management
- Real-time form validation
- Success notifications
- Automatic inventory updates

## Tech Stack

- **Framework**: Next.js 13 with App Router
- **Styling**: Tailwind CSS
- **UI Components**: shadcn/ui
- **Charts**: Recharts
- **Icons**: Lucide React
- **Form Handling**: React Hook Form + Zod
- **Notifications**: Sonner
- **Theme**: Next Themes (Dark/Light mode)

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```
4. Open [http://localhost:3000](http://localhost:3000) in your browser

## Project Structure

```
├── app/                 # Next.js app directory
│   ├── inventory/      # Inventory management page
│   ├── products/      # Product registration page
│   └── page.tsx       # Revenue analysis page
├── components/         # React components
│   ├── inventory/     # Inventory-related components
│   ├── layout/        # Layout components
│   ├── products/      # Product-related components
│   ├── revenue/       # Revenue-related components
│   └── ui/            # UI components
└── lib/               # Utilities and data
```

## Key Features

### Interactive Charts
- Area charts for revenue visualization
- Bar charts for order tracking
- Pie charts for category distribution
- Real-time data updates

### Responsive Design
- Mobile-first approach
- Adaptive layouts
- Touch-friendly interfaces
- Smooth animations

### Theme Support
- Light/Dark mode
- System preference detection
- Persistent theme selection
- Custom color schemes

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request
