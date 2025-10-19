# FitDevs - Trainer Dashboard & Client Management System

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![GitHub stars](https://img.shields.io/github/stars/Ritikshroff/Fit-Devs-fit-India?style=social)](https://github.com/Ritikshroff/Fit-Devs-fit-India/stargazers)

A comprehensive Trainer Dashboard and Client Management System built with Next.js, Node.js, and MongoDB. This platform helps fitness trainers manage their clients, track progress, and streamline their coaching business.

## 🚀 Features

- **Trainer Dashboard** - Overview of clients, schedules, and metrics
- **Client Management** - Track client profiles, goals, and progress
- **Workout & Diet Plans** - Create and assign customized plans
- **Progress Tracking** - Visualize client progress with charts
- **Payment Integration** - Manage subscriptions and payments
- **Notifications** - Email/WhatsApp reminders and updates
- **Responsive Design** - Works on desktop and mobile devices

## 🛠 Tech Stack

- **Frontend**: Next.js 14, Tailwind CSS, Chart.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB with Mongoose
- **Authentication**: NextAuth.js
- **Payments**: Razorpay/Stripe
- **Notifications**: Nodemailer, Twilio (WhatsApp)
- **Deployment**: Vercel (Frontend), Render/Railway (Backend)

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ and npm/yarn
- MongoDB Atlas account
- Git

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Ritikshroff/Fit-Devs-fit-India.git
   cd Fit-Devs-fit-India
   ```

2. **Install dependencies**
   ```bash
   # Install frontend dependencies
   cd frontend
   npm install
   
   # Install backend dependencies
   cd ../backend
   npm install
   ```

3. **Environment Setup**
   - Copy `.env.example` to `.env` in both frontend and backend directories
   - Update the environment variables with your configuration

4. **Run the application**
   ```bash
   # Start frontend (from frontend directory)
   npm run dev
   
   # Start backend (from backend directory)
   npm run dev
   ```

   The application will be available at `http://localhost:3000`

## 🤝 Contributing

We welcome contributions! Please read our [Contributing Guidelines](CONTRIBUTING.md) to get started.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Next.js Documentation](https://nextjs.org/docs)
- [Tailwind CSS](https://tailwindcss.com/)
- [MongoDB](https://www.mongodb.com/)
- [Chart.js](https://www.chartjs.org/)
