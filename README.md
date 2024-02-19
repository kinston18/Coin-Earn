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

You can start editing the page by modifying `app/page.js`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

### Problem Statement
You need to create a web application for students where they can create profiles, earn coins based on profile building, and apply for internships through the platform using those coins.
Quick Task:
1. Authentication for Students
2. Registration through Email with OTP; no password required.
3. Create a Profile and earn coins related to fields.
4. While filling in the input, the user can see the total coins earned (real-time coins) in the header.
5. Fetch 100 internships from the Internshala API/Web Scraping (find some way to obtain the list of internships), or you can use any other platform if Internshala is not working.
6. Job/Internship Details to display on the card:
  1. Role Name
  2. Company Name
  3. Company Logo
  4. CTC/Stipend
  5. Experience Required
  6. Button - Apply using 50 coins
7. Students will spend 50 coins on every application.
8. When the user clicks on apply, you have to check if the user has enough coins or not.
  1. If there are enough coins:
    1. Applied Successfully
  2. Show a popup indicating insufficient coins to apply.
    1. Oops! You don't have sufficient balance
9. List of all applied internships.
10. Display all the internships users applied for with coins spent.
11. Logout.
