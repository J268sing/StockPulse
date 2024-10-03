# Stock Picker


Demo web app using Next.js, React Server Components, and Streaming "server-rendered" stock price data from Polygon.io API.

This project uses the brand new shadcn/ui charts library - https://ui.shadcn.com/charts.

# Features

- Built with Next.js App Router, Typescript, TailwindCSS, and Shadcn/UI (and latest charting components)
- Uses React Server Components and Streaming "server-rendered" stock price data from Polygon.io API

# Getting Started

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/J268sing/stock-pulse.git
   ```

2. Move to the cloned directory

   ```bash
   cd stocks
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Copy the .env.example to your .env.local

   ```bash
   cp .env.example .env.local
   ```

5. Get your API Key from [Polygon.io](https://polygon.io/) and paste it into your .env.local

6. Run the development server:

   ```bash
   npm run dev
   ```
