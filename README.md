# 🚀 Maverick Start Program — Mobile Engineering (Flutter) Pre-Assessment

Welcome to the **Maverick Start Program Pre-Assessment** for Flutter interns. This assessment is your opportunity to demonstrate your ability to design and build a real-world, user-centered mobile app using Flutter. At **Payd**, we value deep product thinking, strong coding practices, attention to user needs, and the creativity to think beyond constraints, the Maverick way.

---

## 🧠 Objective

You are required to build a **functional mobile banking prototype using Flutter**, tailored for a specific user segment of your choice. The goal is to assess:

- Your understanding of mobile product development
- Your ability to build a modular, well-structured Flutter app
- Your use of state management, local storage, and routing
- Your ability to simulate user flows with a good UX
- Your thinking around real-world problem-solving for underserved markets

---

## 🎯 The Challenge

You will build a mobile banking app with the following **core functionality**:

### 🔐 1. Authentication Flow
- Login and signup screens (mocked or stored locally)
- PIN setup and secure login using the PIN
- Optional biometric login (bonus)

### 💼 2. Wallet Dashboard
- Show wallet balance, account info, and recent transactions
- Support for multiple currency balances (e.g. USD, KES)
- Display a list of incoming and outgoing payments

### 💸 3. Send & Receive Money
- Allow users to send money to another user using email or phone number
- Simulate receiving money (via a mock trigger)
- Transaction success/failure states
- Transaction receipts (mocked)

### 📊 4. Transaction History & Insights
- Show full list of transactions
- Filter by date, transaction type
- Basic analytics (total sent, total received, recent activity)

### 🧑 5. User Profile & Settings
- Update user info (locally stored)
- Reset PIN
- Light/dark mode toggle

---

## 📂 Project Structure Requirements

Use a **modular folder structure** to organize your code. Suggested structure:

```bash
lib/
├── main.dart
├── core/              # themes, constants, helpers
├── models/            # data models for user, transactions, etc
├── services/          # local db, auth service, storage
├── features/
│   ├── auth/          # login, register, PIN setup
│   ├── dashboard/     # home/wallet screens
│   ├── transactions/  # transaction history, details
│   └── profile/       # settings and profile
├── widgets/           # reusable UI components
assets/
├── icons/
├── images/
```

---

## 📚 Tech Requirements

- **Flutter SDK:** Latest stable version
- **State Management:** Provider, Riverpod, Bloc, or GetX (explain your choice)
- **Routing:** GoRouter or Flutter's native Navigator 2.0
- **Local Storage:** Hive, SharedPreferences, or SQLite
- **Responsiveness:** App must work on multiple device sizes
- **Error Handling:** Proper try/catch, null safety practices
- **Clean Code Practices:** Separation of concerns, DRY code, and documentation

---

## 👥 Target Audience (Choose One)

Pick one segment and build the app tailored to their use case:

- Freelancers in Africa (e.g. Upwork, Fiverr) receiving global payments
- Event organizers collecting payments for events or content
- Remote teams paying international contractors
- Student groups or Saccos pooling funds
- Creators monetizing content with tips or subscriptions

> Clearly define the user persona and use case in your README.

---

## 🔧 Feature Expectations (Summary)

| Feature                          | Required |
|----------------------------------|----------|
| Login/Signup with PIN auth       | ✅        |
| Wallet dashboard (multi-currency)| ✅        |
| Send/Receive simulation          | ✅        |
| Transaction list + filters       | ✅        |
| Local storage (wallet, tx)       | ✅        |
| Profile + PIN reset              | ✅        |
| Light/Dark mode                  | ✅        |
| Biometric login                  | 🔁 Bonus |
| Transaction analytics/dashboards| 🔁 Bonus |

---

## 📌 Submission Instructions

1. **Create a repository for the project** in your GitHub account
2. **Build your project** inside your repo
3. **Update the `README.md`** in your repo to include:
   - Your full name
   - Target user segment
   - Summary of features implemented
   - Tech stack and libraries used
   - Setup instructions to run the app
   - Your product thinking (why you built what you built)
   - (Optional) Link to a Loom or YouTube video walkthrough
4. Once complete, **make the repo public and share via email** to ravens@payd.money for review

---

## 🕒 Timeline

- There is no specific submission timeline, but this is part of the assesment.
- **Hint:** We are merchants of moving fast and making things

---

## 🧭 Evaluation Criteria

| Criteria                     | Weight |
|------------------------------|--------|
| Product Thinking              | 20%    |
| Code Structure & Practices    | 25%    |
| UI/UX Quality                 | 20%    |
| State Management & Logic      | 15%    |
| Time taken to complete        | 10%    |
| Completeness & Documentation  | 10%    |

---

## 🌟 Bonus Points

- Beautiful animations & micro-interactions
- Insightful transaction analytics or dashboards
- Multi-wallet or currency support
- Additional useful features for the specific user segment

---

## 💬 Questions?

Please reach out through the team via email to ravens@payd.money if you need clarification.

---

### Build boldly. Design clearly. Think like a Maverick.

—  
**Team Payd**
