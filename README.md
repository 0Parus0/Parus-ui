


# ParusUI-Digital Marketplace for UI Components
A digital marketplace where users can buy and sell UI components like templates, UI kits, and icons. The buyer will get an email containing the prodouct been bought and the seller will get the 90% of the sale and remaining 10% will be divided between Stripe and The PausUI. This project showcases my Next.js skills, frontend design, and a very secure payment processing including not only one time  payments with Stripe checkout but the Market place will get it's share using Stripe connect as well and usage of web hooks. An integration of text editor in the app where seller can describe his product.

## Demo
Check out the live demo [here](https://parus-ui.vercel.app/).



## Features

- **User Auth/Registration/Profile:** Sign up, log in, manage profile and multi-factor auth.
- **Search/Sort/Filter/Pagination:** Search different items like Icons pack, UI Templates, and UI kits.
- **Stripe checkout & Stripe Connect :** Create a Stripe connect Account, Which lets the market place gets its share .
- **Strip-Express dashboard:** Seller can login and can check all of the transactions happend on his product.
- **Real-Time Updates:** Add items to the cart and update orders in real-time.
- **Responsive Design:** Optimized for mobile, tablet, and desktop.
- **Supabase + Prisma:** Supabase for hosting PostgressQl database and Prisma for TypeScript ORM.
- **File & Image Uploads:** Uploading files and images to uploadthing which uses AWS S3.
- **Rich Text Editor:** A rich text editor built into the market place, for seller to describe his product.
- **Vercel: ** Hosted on Vercel.

## Technologies Used

- **Frontend:** TypeScript, Nextjs, TipTap Editor, React Hook Form, TailwindCss, and ShadcnUI.
- **Backend:** TypeScript, Next.js.
- **Database:** SupabaseDB, PostgressQl, Prisma ORM
- **Others:** GitHub, Kinde for authentication, Stripe checkout & Stripe Connect, Uploadthing.

## Getting Started

To get a local copy up and running, follow these steps.

### Prerequisites

- Node.js and npm
- MongoDB (for the database)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/0Parus0/parus-ui.git
   cd food-ordering-app

2. **Install dependencies:**
  ```bash
  npm install
```
3. **Run:**
  ```bash
  npm run dev
  ```

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
