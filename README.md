# AgentSupply

A modern, AI-powered dashboard for supply chain management built with Next.js, TailwindCSS, and OpenAI.

![AgentSupply](public/dashboard-preview.png)

## Features

### 🔄 Dynamic KPIs
- Real-time metrics for inventory levels, shipment status, and supplier performance
- Customizable dashboard with drag-and-drop widgets
- Threshold-based highlighting for critical metrics

### 🌓 Light/Dark Mode
- Seamless theme switching with system preference detection
- Optimized color schemes for both modes
- Persistent user preference

### 📦 Inventory Tracking
- Real-time inventory levels across all warehouses
- Low stock alerts and reorder recommendations
- Historical inventory trends with predictive analytics

### 🚚 Shipment Tracking
- Live tracking of all shipments with geolocation data
- Delivery time predictions with AI-powered ETA
- Delay risk assessment and mitigation suggestions

### 👥 Supplier Management
- Comprehensive supplier database with performance metrics
- Risk assessment for each supplier based on historical data
- Communication tools integrated with the platform

### ⚠️ Auto-Alerts
- Intelligent alert system for inventory, shipments, and suppliers
- Customizable notification thresholds
- Multi-channel alerts (in-app, email, SMS)

### 🧠 AI Insights (OpenAI)
- AI-powered supply chain risk prediction
- Natural language processing for trend analysis
- Automated recommendations for optimization

### 📊 Reports & Analytics
- Interactive charts and graphs using Recharts
- Exportable reports in multiple formats
- Custom report builder with saved templates

### 💬 AI Assistant
- Integrated chatbot for quick queries and insights
- Natural language interface to your supply chain data
- Contextual recommendations based on user role

## Tech Stack

- **Frontend**: Next.js 14 (App Router), TailwindCSS, Shadcn UI, Recharts
- **Backend**: Next.js API Routes with MongoDB Atlas
- **AI**: OpenAI API for forecasting and insights

## Getting Started

### Prerequisites

- Node.js 18+ and npm
- MongoDB Atlas account
- OpenAI API key

### Installation

1. Clone the repository:
\`\`\`bash
git clone https://github.com/yourusername/supply-chain-ai-dashboard.git
cd supply-chain-ai-dashboard
\`\`\`

2. Install dependencies:
\`\`\`bash
npm install
\`\`\`

3. Create a `.env.local` file in the root directory with the following variables:
\`\`\`
# MongoDB
MONGODB_URI=your_mongodb_atlas_connection_string

# OpenAI
OPENAI_API_KEY=your_openai_api_key

# Next Auth (if implementing authentication)
NEXTAUTH_SECRET=your_nextauth_secret
NEXTAUTH_URL=http://localhost:3000
\`\`\`

4. Run the development server:
\`\`\`bash
npm run dev
\`\`\`

5. Open [http://localhost:3000](http://localhost:3000) in your browser to see the dashboard.

## Deployment

This project is ready for deployment on Vercel:

1. Push your code to a GitHub repository
2. Import the project in Vercel
3. Configure the environment variables
4. Deploy!

## License

MIT

## Acknowledgements

- [Next.js](https://nextjs.org/)
- [TailwindCSS](https://tailwindcss.com/)
- [Shadcn UI](https://ui.shadcn.com/)
- [Recharts](https://recharts.org/)
- [OpenAI](https://openai.com/)
- [MongoDB Atlas](https://www.mongodb.com/atlas)
