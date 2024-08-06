# Price Monitor

Price Monitor is a Next.js application that leverages web scraping to track product prices across various online stores. It helps users stay informed about price changes and get the best deals on their desired products.

## Features

- **Real-time Price Tracking**: Continuously monitors product prices from multiple online retailers.
- **User Notifications**: Sends alerts when prices drop or reach a specified threshold.
- **Historical Data**: Provides a history of price changes for each tracked product.
- **Customizable Watchlist**: Allows users to add and manage their favorite products.
- **Responsive Design**: Ensures a seamless experience across different devices.

## Tech Stack

- **Frontend**: Next.js, React, Tailwind CSS
- **Backend**: Node.js, Express
- **Web Scraping**: Puppeteer, Cheerio
- **Database**: MongoDB
- **Authentication**: NextAuth.js

## Getting Started

### Prerequisites

- Node.js (v14.x or later)
- MongoDB

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/price-monitor.git
   cd price-monitor
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Set up environment variables**:
   Create a `.env.local` file in the root directory and add the following variables:
   ```
   MONGODB_URI=your_mongodb_connection_string
   NEXTAUTH_URL=http://localhost:3000
   ```

4. **Run the application**:
   ```bash
   npm run dev
   ```

   The application will start on `http://localhost:3000`.


## Acknowledgements

- [Next.js](https://nextjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Puppeteer](https://pptr.dev/)
- [Cheerio](https://cheerio.js.org/)
- [MongoDB](https://www.mongodb.com/)
- [NextAuth.js](https://next-auth.js.org/)

---