# Fullstack <a href='https://jotion-x.vercel.app/' target='_blank'><u>Jotion</u></a> (Notion Clone) : Next.js 14, React, Convex, TailwindCss, Shadcn, ClerkAuth

![Overview](https://github.com/MahdiELHasra/Jotion-x-note-taking/assets/114767917/8f39c5aa-ba1b-4cd4-87bc-7aeaebbd527f)

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

Key Features:

- Real-time database synchronization 🔗
- Notion-style text editor 📝
- Dual theme support: Light and Dark mode 🌓
- Infinite hierarchical document structure 🌲
- Trash can functionality with soft delete option 🗑️
- Secure authentication system 🔐
- Capability for file uploads
- File deletion functionality
- File replacement feature
- Dynamic icons associated with each document (updates in real-time) 🌠
- Expandable sidebar with directional controls ➡️🔀⬅️
- Complete mobile responsiveness for seamless access on any device 📱
- Ability to publish your notes to the web 🌐
- Fully collapsible sidebar for enhanced interface flexibility ↕️
- Integrated landing page feature for user convenience 🛬
- Cover image customization for each document 🖼️
- File recovery option for retrieving deleted files 🔄📄

### Cloning the repository

```shell
git clone https://github.com/MahdiELHasra/Jotion-x-note-taking.git
```

### Install packages

```shell
npm install
```

### Setup .env file

```js
# Deployment used by `npx convex dev`
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

EDGE_STORE_ACCESS_KEY=
EDGE_STORE_SECRET_KEY=
```

### Setup Convex

```shell
npx convex dev
```

### Start the app

```shell
npm run dev
```

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
