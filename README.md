# hrm-superadmin
Superadmin HRM Frontend
A modern React-based Human Resource Management (HRM) system frontend built with Vite, designed for superadmin functionality with comprehensive package management, user administration, and coupon management features.

🚀 Tech Stack

React 18 - Modern React with hooks
Vite - Fast build tool and development server
Yup - Schema validation for forms
ESLint - Code linting and formatting

📋 Features

Package Management
Create and manage subscription packages
Configure pricing for different currencies (INR/USD)
Set up offer percentages and promotional pricing
Category-based package organization
Free and paid plan support
Coupon Management
Create discount coupons with percentage-based offers
Set validity periods with date ranges
Package-specific coupon assignments
Coupon status management
User Administration
Admin user management
Password reset functionality
Country and company information management
Form Validation
Comprehensive form validation using Yup schemas
Real-time validation feedback
Custom validation rules for business logic
🛠️ Installation
Clone the repository

git clone <repository-url>
cd Superadmin_hrm_frontend
Install dependencies

npm install
Start development server

npm run dev
Build for production

npm run build


📁 Project Structure
Superadmin_hrm_frontend/
├── src/
│   ├── schemas/
│   │   └── index.jsx          # Yup validation schemas
│   └── ...
├── public/
├── package.json
└── README.md
🔧 Available Scripts

npm run dev - Start development server with HMR
npm run build - Build for production
npm run preview - Preview production build
npm run lint - Run ESLint

📝 Form Schemas
The project includes comprehensive validation schemas for:

Package Management: Plan creation, pricing, features, and categories
Coupon Management: Discount percentages, validity periods, and package assignments
User Management: Password validation and user information
Category Management: Feature categorization and validation
🎯 Key Validation Features
Multi-currency Support: Separate validation for INR and USD pricing
Conditional Validation: Different rules for free vs paid plans
Date Validation: Ensures logical date ranges for coupons and offers
Percentage Validation: Proper bounds checking for discount percentages
String Validation: Alphanumeric checks and length constraints

🔒 Validation Rules

Package Validation
Plan names: 3-50 characters
Descriptions: 10-80 characters
Prices: Positive numbers only
GST: Required for paid plans
Features: Minimum one feature required
Coupon Validation
Percentage: 0-100% range
Date ranges: To date must be after from date
Package selection: Required field

🚦 Development Guidelines

Form Validation: Always use the provided Yup schemas for form validation
Error Handling: Implement proper error messages for user feedback
Code Style: Follow ESLint rules for consistent code formatting
Component Structure: Keep components modular and reusable

🤝 Contributing

Fork the repository
Create a feature branch (git checkout -b feature/new-feature)
Commit your changes (git commit -am 'Add new feature')
Push to the branch (git push origin feature/new-feature)
Create a Pull Request

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

🆘 Support
For support and questions, please contact the development team or create an issue in the repository.

Built with ❤️ using React + Vite
