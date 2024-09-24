<h1 align="center">OnlyFans but for Horses 🐴</h1>

![Demo App](/public/demo-for-readme.png)


Some Features:

-   ⚛️ Tech Stack: Next.js 14, TypeScript, Tailwind CSS, Prisma, PostgreSQL, Stripe
-   🔐 Authentication with Kinde Auth
-   💸 Monthly and Annually Subscriptions with Stripe.
-   💰 One Time Payments with Stripe
-   💵 Building a Stripe Billing Portal
-   🛒 E-Commerce Store
-   ✉ Sending "Successful Payment" Emails to Users
-   ✍️ Creating Posts
-   💬 Commenting on Posts
-   ❤️ Liking Posts
-   🔒 Secret Admin Dashboard
-   📝 Data Aggregation with Prisma
-   🖼️ Edit Profile
-   📷 Image/Video Uploads using Cloudinary
-   💙 Awesome Landing Page
-   🌐 Deployment
-   👀 And Millions of Other Cool Features

### Images

Auth Page
<img width="1440" alt="Screenshot 2024-09-24 at 6 38 40 PM" src="https://github.com/user-attachments/assets/83c803aa-d3a1-4d19-804f-7e9b2e53cc22">

Home Page
<img width="1440" alt="Screenshot 2024-09-24 at 6 40 45 PM" src="https://github.com/user-attachments/assets/e22ee281-e02f-4259-9d69-7aae63f64c49">

Secret-dashboard
<img width="1440" alt="Screenshot 2024-09-24 at 6 33 37 PM" src="https://github.com/user-attachments/assets/50b371fc-19d5-4969-9364-1d59d617bf57">

Our Products
<img width="1440" alt="Screenshot 2024-09-24 at 6 37 17 PM" src="https://github.com/user-attachments/assets/51118767-ad1c-4af9-84f7-a7aac666c877">

Pricing
<img width="1440" alt="Screenshot 2024-09-24 at 6 40 59 PM" src="https://github.com/user-attachments/assets/6674d0cd-7943-484d-a606-01c43cac97fe">


### Setup .env file

```js
// kinde
KINDE_CLIENT_ID=<get_from_kinde>
KINDE_CLIENT_SECRET=<get_from_kinde>
KINDE_ISSUER_URL=<get_from_kinde>
KINDE_SITE_URL=<get_from_kinde>
KINDE_POST_LOGOUT_REDIRECT_URL=<get_from_kinde>
KINDE_POST_LOGIN_REDIRECT_URL=<get_from_kinde>

// cloduinary
NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=<get_from_cloudinary>
NEXT_PUBLIC_CLOUDINARY_API_KEY=<get_from_cloudinary>
CLOUDINARY_API_SECRET=<get_from_cloudinary>

DATABASE_URL=<any_postgres_db_url>

ADMIN_EMAIL=<your_email>

// stripe
STRIPE_SECRET_KEY=<get_from_stripe>
STRIPE_WEBHOOK_SECRET_DEV_KEY=<get_from_stripe>
STRIPE_WEBHOOK_SECRET_LIVE_KEY=<get_from_stripe>
NEXT_PUBLIC_STRIPE_DEV_MONTHLY_URL=<get_from_stripe>
NEXT_PUBLIC_STRIPE_LIVE_MONTHLY_URL=<get_from_stripe>
NEXT_PUBLIC_STRIPE_DEV_YEARLY_URL=<get_from_stripe>
STRIPE_MONTHLY_PLAN_PRICE_ID=<get_from_stripe>
STRIPE_YEARLY_PLAN_PRICE_ID=<get_from_stripe>
STRIPE_BILLING_PORTAL_LINK_DEV=<get_from_stripe>

// resend
RESEND_API_KEY=<get_from_resend>

NEXT_PUBLIC_BASE_URL=http://localhost:3000
```

### Install dependencies

```shell
npm install
```

### Start the app

```shell
npm run dev
```

<hr/>

# OnlyFans
