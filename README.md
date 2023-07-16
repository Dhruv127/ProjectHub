# Welcome to Project HUB

A comprehensive platform that integrates various ai-powered tools and useful websites

## Live demo

The site is deployed through Vercel, which you can view from [here](project-hub-olive.vercel.app) <br>

## 🚀 Main Features

* Login Page
* Data storage in MongoDB cluster
* Approval System
* Role-based Authentication
* Homepage
* Add project page
* Contact page
* Admin page (accessible only to admin)
* Message page (admin only)
* Custom Loader
* Notifications

## 💻 Tech Stack

* Nextjs
* Typescript
* NextAuth
* Tailwindcss
* MongoDB
* Docker
* React-Toast

🤝 Credits

## Prerequisites

Required to install and run the software:

* pnpm

If you don't have pnpm installed, you can install it by following the below steps : 

Using npm <br>

```bash
npm install -g pnpm
```
Alternatively you can delete the pnpm-lock.yaml file and install the dependencies with either ``yarn`` or ``npm`` <br>

This is a Next.js project bootstrapped with create-next-app

## 🌟 Getting Started

create a .env file and paste the follwing content in there : 

```
GITHUB_ID=""
GITHUB_SECRET=""
GOOGLE_ID=""
GOOGLE_SECRET=""
SECRET=""
MONGODB_URI=""
NEXT_PUBLIC_ADMIN_EMAIL=""
```
Now, create your own credentials for the providers and MongoDB cluster and place them in the corresponding fields ,put the email in the `NEXT_PUBLIC_ADMIN_EMAIL` field which you want to give admin privileges

From the project folder, run these commands in the console (terminal) to install dependencies and run the app:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

# 🖼️ Some glimpse of the site

### Login Page 

<img width="1440" alt="Screenshot 2023-07-16 at 7 17 10 PM" src="https://github.com/Tushar98644/ProjectHub/assets/107763774/1faa0b9a-afca-443e-815c-ddfa35154121">

### Home Page

<img width="1440" alt="Screenshot 2023-07-16 at 7 20 59 PM" src="https://github.com/Tushar98644/ProjectHub/assets/107763774/b81a1a90-9585-47ed-b781-d1f3b76acae3">

### Add Project Page

<img width="1440" alt="Screenshot 2023-07-16 at 7 23 03 PM" src="https://github.com/Tushar98644/ProjectHub/assets/107763774/cbb315fa-a970-4e6b-b4df-d6d0f83248f4">

### Contact Page 

<img width="1440" alt="Screenshot 2023-07-16 at 7 25 11 PM" src="https://github.com/Tushar98644/ProjectHub/assets/107763774/412f1518-8b87-489e-83cc-024aa957973a">

### Admin Page

<img width="1440" alt="Screenshot 2023-07-16 at 7 24 40 PM" src="https://github.com/Tushar98644/ProjectHub/assets/107763774/da4e7314-36db-492a-9307-c98a1825229f">

### Message Page

<img width="1440" alt="Screenshot 2023-07-16 at 7 27 31 PM" src="https://github.com/Tushar98644/ProjectHub/assets/107763774/f83c3497-e2fa-4be5-8929-ace92ab9457f">

## 🐛 Bug Reporting
Feel free to open an [issue](https://github.com/Tushar98644/ProjectHub/issues/new?assignees=&labels=bug&projects=&template=bug_report.yaml&title=%5BBUG%5D+%3Ctitle%3E) on GitHub if you find any bug.

## ⭐ Feature Request
Feel free to Open an [issue](https://github.com/Tushar98644/ProjectHub/issues/new/choose) on GitHub to request any additional features you might need for your use case.

## 📜 License
This software is open-source, licensed under the [MIT License](https://github.com/Tushar98644/ProjectHub/blob/main/LICENSE).

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme)

Check out the [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
