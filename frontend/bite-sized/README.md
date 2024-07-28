Grab Food Discovery Extension

## Overview

BiteSized is an innovative food browsing extension for GrabFood and GrabMart. It features AI-generated visuals to boost marketing and attract engagement. Users can swipe right to order their cravings and swipe left to explore more options. BiteSized uses a MERN stack (MongoDB, Express, React, Node.js) ensure scalability and feasibility. They also use Python's Beautiful Soup to gathering menu data from restaurants. Moreover, BiteSized creates their content using Stability AI's stable diffusion. Whether you’re a busy professional, health-conscious foodie, or suburban parent, this extension simplifies your dining experience.

BiteSized aims to be a creative and scalable AI solution to improve user experience within the Grab app, drive economic growth, and empower individuals and businesses within Southeast Asia.

## Features

1. AI-Generated Videos: Engage users with mouthwatering videos for each menu item.
2. Swipe-to-Order Interaction: Simplify the ordering process—swipe right to order, left to explore more.

## Tech Stack

BiteSized is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

Frontend:
 - React (built on the MERN stack)
 - Responsive design for mobile and desktop
Backend:
 - Node.js (Express framework)
 - MongoDB for data storage
Web Scraping:
 - Python with Beautiful Soup for menu data extraction
AI Model:
 - Stability AI’s Stable Diffusion Model for generating visuals

## Installation

First, Clone this repository.

Then, install dependencies:
```bash
npm install
npm install react-swipeable
```

Finally, Set up your environment variables, such as the database connection and API keys.

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

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.