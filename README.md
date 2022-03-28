# Clerk - Gatsby starter

<img src="./docs/logo.png" />

This repository shows how to add [Clerk](https://clerk.dev) to a [Gatsby](https://gatsbyjs.com/) app.

You can find its live demo at [https://starter.gatsby.clerk.app](https://starter.gatsby.clerk.app).

[![Open in VS Code](https://open.vscode.dev/badges/open-in-vscode.svg)](https://open.vscode.dev/clerkinc/clerk-gatsby-starter)

## Under the hood

This starter uses `gatsby-plugin-clerk`, which wraps `ClerkProvider` around the whole app. With that, you can start using components from `@clerk/clerk-react` — such as `SignedIn` and `SignedOut` — on the root of your app.

## Running the starter locally

1. Fork and clone this repository
2. Install dependencies: `yarn install`
3. Add your environment variables to a file called `.env.development`:
   1. Set the "Frontend API" variable, found on your Clerk dashboard, under the **Home** tab: `echo "GATSBY_CLERK_FRONTEND_API_URL=YOUR_FRONTEND_API_URL" >> .env.development`
   2. Set the "API key" variable, found on your Clerk dashboard, on the **Settings** page, under the **API keys** tab: `echo "CLERK_API_KEY=YOUR_API_KEY" >> .env.development`
4. Run the app: `yarn start`

## Need help?

If you need any [assistance](https://clerk.dev/support), we're happy to help you out!
