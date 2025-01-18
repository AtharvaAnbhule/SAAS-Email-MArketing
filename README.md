# Email Marketing Application

This is a comprehensive Email Marketing Application built with Next.js, Prisma, and PostgreSQL. It provides a robust platform for managing email marketing campaigns with features like automated AI chatbots, appointment bookings, payment processing, and more.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Automated AI Sales Rep**: Chatbot for booking appointments and processing payments.
- **Website Integration**: Usable on any website with a simple code snippet.
- **Smart Question Linking**: Intelligent linking of questions for better user experience.
- **Real-Time Chat**: Supports both manual and automated chat.
- **White-Labeling Options**: Customizable branding for different clients.
- **Customizable Interface**: Easily modify the interface to suit your needs.
- **Calendar Widget**: Allows users to book appointments directly.
- **Stripe Integration**: Secure payment processing through Stripe.
- **Email Marketing**: Simple yet powerful email marketing tools.
- **Financial Dashboard**: Detailed financial insights and reports.
- **Lead Management**: Save visitor information as leads.
- **Custom Authentication**: Login and signup with OTP.
- **Secure File/Image Uploads**: Safeguard your uploads.
- **SEO Optimized Blogging**: Boost visibility with SEO-friendly blog posts.
- **Improved Architecture**: Designed for scalability and performance.
- **Minimal, Stunning UI**: Clean and modern user interface.
- **FAQ Section**: Comprehensive FAQ for user assistance.
- **Light/Dark Mode**: Toggle between light and dark themes.
- **Feature Control Settings**: Manage features based on different plans.
- **Plan-Based Restrictions**: Restrict features according to user subscription plans.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/AtharvaAnbhule/SAAS-Email-MArketing.git
   cd email-marketing-app
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Set up the environment variables**:
   Create a `.env` file in the root directory and add your environment variables. Refer to `.env.example` for guidance.

4. **Run the development server**:
   ```bash
   npm run dev
   ```

5. **Database migration**:
   ```bash
   npx prisma migrate dev
   ```

## Usage

- Access the development server at `http://localhost:3000`.
- Use the admin dashboard to manage email campaigns, leads, and financial reports.
- Integrate the chatbot into any website using the provided code snippet.
- Customize the user interface through the settings panel.

## Configuration

- **Prisma**: Configure your database schema and models using Prisma.
- **PostgreSQL**: Ensure PostgreSQL is properly set up and connected.
- **Stripe**: Set up Stripe API keys for payment processing.
- **Email Marketing**: Configure SMTP settings for sending emails.

## Deployment

1. **Build the application**:
   ```bash
   npm run build
   ```

2. **Start the production server**:
   ```bash
   npm start
   ```

3. **Deploy to a cloud platform** like Vercel, AWS, or any platform of your choice.

## Contributing

We welcome contributions! Please read our [Contributing Guidelines](CONTRIBUTING.md) for more details.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

