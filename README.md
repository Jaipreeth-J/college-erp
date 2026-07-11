# College ERP

Attendance and academic management system.

## Technologies Used

- Vite
- TypeScript
- React
- shadcn-ui
- Tailwind CSS
- Supabase

## Getting Started

### Prerequisites

- Node.js & npm installed

### Installation

1. Clone the repository
2. Navigate to the project directory: `cd College-ERP-main`
3. Install dependencies: `npm i`

### Environment Variables

This project uses Supabase for the backend. You need to set up your environment variables.

1. Copy `.env.example` to `.env`
   ```sh
   cp .env.example .env
   ```
2. Fill in your Supabase credentials in the `.env` file:
   - `VITE_SUPABASE_URL`: Your Supabase project URL
   - `VITE_SUPABASE_ANON_KEY`: Your Supabase anon/public key

### Running the App

Start the development server:

```sh
npm run dev
```

The app will be available at `http://localhost:8080` (or another port if 8080 is taken).

## Deployment

You can deploy this project using Vercel, Netlify, or any other standard hosting provider for Vite applications. Remember to configure the environment variables (`VITE_SUPABASE_URL` and `VITE_SUPABASE_ANON_KEY`) in your hosting provider's dashboard.
