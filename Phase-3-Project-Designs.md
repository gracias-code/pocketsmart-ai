# Phase 3 – Project Design

## Project Name
ProjectSmart AI

## Subtitle
Your Smart Budget & Recommendation Assistant

## 1. System Architecture

ProjectSmart AI will use a modular web application architecture.

### Frontend
- Responsive SaaS dashboard
- Dashboard
- Transactions
- Budget
- Savings Goals
- AI Assistant
- Insights
- Settings

### Backend
- API layer for application logic
- Budget calculations
- Transaction management
- Savings goal calculations
- Gemini AI integration

### Data Layer
The application will store:
- User profile
- Income
- Expenses
- Categories
- Transactions
- Budgets
- Savings goals
- AI recommendations
- Application settings

### AI Layer
Google Gemini will analyze user-provided financial data and generate:
- Spending observations
- Budget recommendations
- Savings suggestions
- Spending warnings
- Savings goal guidance

The AI will only receive the minimum required financial information.

---

## 2. Main Application Modules

### Dashboard
Displays:
- Monthly income
- Total expenses
- Remaining balance
- Savings amount
- Savings percentage
- Budget utilization
- Savings goal progress
- Expense charts
- Income vs expense chart
- Monthly spending trend

### Transactions
Users can:
- Add transactions
- Edit transactions
- Delete transactions
- Search transactions
- Filter by category
- Filter by date
- Sort by amount

Transaction fields:
- Date
- Description
- Amount
- Category
- Type

### Budget
Users can:
- Set monthly income
- Set category budgets
- Add custom categories
- Edit category budgets
- Delete categories

Budget categories:
- Food
- Transport
- Shopping
- Education
- Bills
- Healthcare
- Entertainment
- Other

### Savings Goals
Users can create:
- College fees
- Laptop
- Emergency fund
- Travel
- Personal goal

Goal fields:
- Goal name
- Target amount
- Current saved amount
- Target date

Calculated values:
- Remaining amount
- Progress percentage
- Required monthly saving

### AI Assistant
The AI Assistant will provide personalized responses based on the user's actual financial data.

Example questions:
- How can I save ₹5,000 this month?
- Where am I overspending?
- Create a budget for my income.
- How much can I save in 6 months?
- Analyze my spending.

The AI will clearly state that its suggestions are educational and not professional financial advice.

### Insights
Displays:
- Highest spending category
- Lowest spending category
- Spending patterns
- Savings progress
- Budget utilization
- AI-generated observations

### Settings
Includes:
- Currency selection
- Dark/light mode
- Basic profile settings
- Load demo data
- Clear all data

---

## 3. Core Calculations

### Total Expenses
Total Expenses = Sum of all expense transactions

### Remaining Balance
Remaining Balance = Monthly Income - Total Expenses

### Savings Amount
Savings Amount = Remaining Balance

### Savings Percentage
Savings Percentage = (Savings Amount / Monthly Income) × 100

### Budget Utilization
Budget Utilization = (Actual Spending / Planned Budget) × 100

### Savings Goal Progress
Progress Percentage = (Current Saved / Target Amount) × 100

### Required Monthly Saving
Required Monthly Saving =
Remaining Goal Amount / Remaining Months

---

## 4. Budget Status Indicators

The application will provide visual indicators:

### Healthy
Spending is comfortably below the budget limit.

### Near Budget Limit
Spending is approaching the budget limit.

### Over Budget
Actual spending has exceeded the planned budget.

---

## 5. User Interface Design

The application will use a premium modern SaaS design.

Design principles:
- Clean layout
- Rounded cards
- Subtle shadows
- Clear typography
- Consistent spacing
- Accessible contrast
- Responsive design
- Smooth transitions
- Light mode
- Dark mode

Default currency:
₹ INR

Supported currencies:
- INR
- USD
- EUR
- GBP

---

## 6. Data Persistence

User data should persist when the page is refreshed.

The application should support:
- Saving user settings
- Saving transactions
- Saving budgets
- Saving savings goals
- Loading saved data
- Clearing all stored data

Demo data should be available for first-time users.

---

## 7. Security Design

Security requirements:
- Never expose Gemini API keys in the client interface.
- Validate all user inputs.
- Do not display private credentials.
- Send only required financial information to the AI service.
- Handle API failures safely.
- Do not store unnecessary personal information.

---

## 8. Error Handling

The application should display friendly messages for:
- Invalid amounts
- Missing inputs
- Invalid dates
- Empty transaction lists
- API failures
- Network errors

Loading states and empty states should be included throughout the application.

---

## 9. Export Feature

Users will be able to export financial information as CSV.

Exported information may include:
- Transaction date
- Description
- Category
- Amount
- Transaction type

---

## 10. Responsive Design

The application will support:
- Desktop
- Laptop
- Tablet
- Mobile

The sidebar may convert into bottom navigation or a mobile menu on smaller screens.

---

## 11. Component Structure

Reusable components will be created for:
- Sidebar
- Navigation
- Cards
- Charts
- Forms
- Transaction table
- Budget cards
- Savings progress bars
- AI chat
- Alerts
- Modal dialogs
- Loading states
- Empty states

---

## 12. Development Priority

The application will be developed in the following order:

1. Project setup
2. Application layout
3. Navigation
4. Dashboard
5. Budget management
6. Transaction management
7. Savings goals
8. Data persistence
9. Charts and insights
10. Gemini AI integration
11. Alerts
12. CSV export
13. Settings
14. Responsive design
15. Testing and error handling

---

## 13. Final Goal

ProjectSmart AI should be a functional financial-planning web application rather than a visual mockup.

Major features must work correctly, including:
- Navigation
- Forms
- Calculations
- Transactions
- Budgets
- Savings goals
- Charts
- Data persistence
- AI interactions
- Insights
- Alerts
- CSV export
- Settings

The final application should be fast, maintainable, responsive, secure, and user-friendly.
