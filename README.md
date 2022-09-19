# Next.js Template for Stable Diffusion

This is a [Next.js](https://nextjs.org/) template for  🍌 [Banana](https://www.banana.dev/) users deploying Stable Diffusion on serverless GPUs. Enter your API keys in .env.local and you're ready to party! 🎉

## Getting Started

First, run the development server:

```bash
npm run dev
```

Create a `.env.local` file in your repo with `BANANA_API_KEY=your_api_key` and `BANANA_MODEL_KEY=your_model_key`

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

An [API route](https://nextjs.org/docs/api-routes/introduction) has already been created [http://localhost:3000/api/diffusion](http://localhost:3000/api/diffusion). This endpoint uses the Banana API keys you provide and can be edited at `pages/api/diffusion.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## 🍌 Banana Docs

To learn more about Banana, take a look at the following resources:

- [Banana Documentation](https://www.banana.dev/docs) - learn about Banana's API.
- [1-Click Stable Diffusion model on Banana](https://www.banana.dev/stable-diffusion) - the world's easiest way to deploy Stable Diffusion on serverless GPUs.

To customize the model beyond the one-click template, see [Banana's GitHub repository](https://github.com/bananaml/serverless-template-stable-diffusion) - full credit goes to Banana for making this project possible!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

Important note: Vercel's "free" plan has a serverless function execution timeout of 10 seconds (this applies to the API route in this project). You will need a "pro" plan (which has a 60 second timeout) to run this in production without issues. This limitation does not affect local development.

## Use Banana for scale.
