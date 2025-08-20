## Try it out!
This project is deployed on railway and can be accessed at:
https://palette-production.up.railway.app/

<img width="2079" height="1360" alt="image" src="https://github.com/user-attachments/assets/c9f9215f-dcee-41b8-b157-9631de081b1f" />


This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## AUTH
We're using nextauth for this simple project.
You'll need to grab OAUTH2 client id / secrets in order to run it.

# GitHub OAuth (Get these from https://github.com/settings/applications/new)
# Google OAuth (Get these from https://console.cloud.google.com/apis/credentials)

You'll also need to connect to a database to run it locally.
Easiest to kick one off in railway and add the connection URL to your .env file.
See .env.example for the required envvars.

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
