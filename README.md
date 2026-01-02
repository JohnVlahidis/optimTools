# optimTools

🗺️ **Route Planner** - Optimize your delivery routes using Google Maps Geocoding API

## Features

- ✅ Password-protected access
- ✅ Secure API key storage (serverless backend)
- ✅ Route optimization using nearest-neighbor algorithm
- ✅ Support for Greek and Greeklish addresses
- ✅ Direct integration with Google Maps
- ✅ Up to 9 destinations

## Deployment

### Deploy to Vercel (FREE!)

1. **Fork or clone this repository**

2. **Sign up for Vercel**
   - Go to [vercel.com](https://vercel.com)
   - Sign up with your GitHub account (free)

3. **Import your project**
   - Click "Add New Project"
   - Import this repository
   - Click "Deploy"

4. **Configure Environment Variables**
   - After deployment, go to: Project Settings → Environment Variables
   - Add: `GOOGLE_MAPS_API_KEY` = `your_google_maps_api_key`
   - Redeploy the project

5. **Done!** Your app is now live and secure 🎉

### Google Maps API Setup

1. Go to [Google Cloud Console](https://console.cloud.google.com/)
2. Create a new project or select existing one
3. Enable **Geocoding API**
4. Create an API key (Credentials → Create Credentials → API Key)
5. **Important:** Remove HTTP referrer restrictions (Geocoding API doesn't support them)
6. Add the API key to Vercel environment variables

## Local Development

For local testing with Vercel CLI:

```bash
npm install -g vercel
vercel dev
```

Create a `.env` file:
```bash
GOOGLE_MAPS_API_KEY=your_api_key_here
```

## Security

- ✅ API key is stored securely on the server (not exposed to users)
- ✅ Password-protected access
- ✅ Serverless architecture (no server maintenance)

## Default Password

Default password: `route_admin2025` (change this in `index.html` line 369)