# Evently

Welcome to Evently, a comprehensive full-stack web application for managing events. Evently serves as a hub, spotlighting diverse events taking place globally. Featuring seamless payment processing through Stripe, you have the capability to purchase tickets for any event or even initiate and manage your own events.

![evently](https://github.com/TariqKichawele/event-app/assets/105932024/38e33c53-0674-4ce0-8c38-7abef996232b)

**TECHNOLOGIES USED**

**Frontend:**
- Next.js: A React framework for building server-side rendered (SSR) and static web applications.
- TypeScript: A statically typed superset of JavaScript for building scalable and robust applications.
- TailwindCSS: A utility-first CSS framework for styling web interfaces.

**Backend:**
- Node.js: A JavaScript runtime for building server-side applications.

**Others:**
- Stripe: A platform for online payment processing.
- Zod: A TypeScript-first schema declaration and validation library.
- React Hook Form: A library for managing form state in React applications.
- Shadcn: A library for implementing shadow effects in web applications.
- Uploadthing: A library for handling file uploads.

**Features**
- Authentication (CRUD) with Clerk: User management through Clerk, ensuring secure and efficient authentication.
- Events (CRUD):
-Create Events: Users can effortlessly generate new events, providing essential details such as title, date, location, and any additional information.
-Read Events: Seamless access to a detailed view of all events, allowing users to explore event specifics, including descriptions, schedules, and related information.
-Update Events: Empowering users to modify event details dynamically, ensuring that event information remains accurate and up-to-date.
-Delete Events: A straightforward process for removing events from the system, giving administrators the ability to manage and curate the platform effectively.
-Related Events: Smartly connects events that are related and displaying on the event details page, making it more engaging for users.
-Organized Events: Efficient organization of events, ensuring a structured and user-friendly display for the audience, i.e., showing events created by the user on the user profile.
- Search & Filter: Empowering users with a robust search and filter system, enabling them to easily find the events that match their preferences.
- New Category: Dynamic categorization allows for the seamless addition of new event categories, keeping your platform adaptable.
- Checkout and Pay with Stripe: Smooth and secure payment transactions using Stripe, enhancing user experience during the checkout process.
- Event Orders: Comprehensive order management system, providing a clear overview of all event-related transactions.
- Search Orders: Quick and efficient search functionality for orders, facilitating easy tracking and management.

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

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

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
