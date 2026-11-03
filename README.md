# Pinlingo

Expo + React Native client for Android and Windows web, with a Node.js/Express API and MongoDB Atlas.

## Render
Create a MongoDB Atlas database. In Render choose **New + → Blueprint**, select this repository and deploy `render.yaml`. Set `MONGODB_URI` to your Atlas connection string. Render generates `JWT_SECRET`. Check `/health` after deployment.

## Client
`npm install`, set `EXPO_PUBLIC_API_URL=https://YOUR-API.onrender.com`, then `npx expo start`. For Windows preview use `npm run web`; for Android use Expo Go or EAS Build.

The initial curriculum is a reviewed starter set of 15 words/phrases for English, Spanish, French, German, Hebrew and Italian. Flag images use FlagCDN and their URLs are cached in MongoDB. Expand and review translations before a public production launch.
