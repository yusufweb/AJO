# Ajo: Modern Rotating Savings Platform

**Empowering communities through digital financial inclusion.**

Digital Ajo is a modern, web-based platform that digitizes the traditional African cooperative savings system, commonly known as **Ajo**, **Esusu**, or **Adashi**. It allows groups of people to contribute money periodically and receive the entire lump sum payout in turns, bringing unparalleled levels of **trust, automation, and transparency** to a time-tested community practice.

---

## 💡 The Goal

Our mission is to simplify community-based savings and empower people through **digital financial inclusion**. By transforming a trusted social convention into a seamless digital experience, we aim to serve as a foundational financial tool, starting in Nigeria and expanding across the African continent.

---

## ✨ Features

Digital Ajo streamlines the entire cooperative savings lifecycle, ensuring a secure and transparent experience for all members.

* **Group Management:** Easily create and manage new savings groups (**ajo/esusu**) with customizable contribution rules and payout schedules.
* **Automated Transactions:** Seamless, scheduled contributions and secure lump-sum payouts powered by leading African payment processors.
* **Member Control:** Effortlessly invite and manage group members with clear visibility into their status.
* **Real-Time Transparency:** Access a **transparent group ledger** and real-time payout tracking for every member.
* **Instant Updates:** Stay informed with real-time updates and notifications on contributions, payouts, and group activity.
* **Secure Payments:** Integrated with **Paystack** and **Flutterwave** for secure, reliable, and compliant financial transactions.

---

## 🛠 Tech Stack

Ajo is built using a modern, scalable, and high-performance stack for a great user and developer experience.

| Category | Technology | Description |
| :--- | :--- | :--- |
| **Frontend** | **Next.js 15** | Fast, modern React framework for performance and developer efficiency. |
| **Styling** | **TailwindCSS** | Utility-first CSS framework for rapid and consistent UI development. |
| **Backend** | **Firebase** | Firestore (Database), Authentication, and Cloud Functions (Serverless logic). |
| **Payments** | **Paystack / Flutterwave** | Robust APIs for seamless and secure payment processing in Africa. |
| **Deployment** | **Vercel** | High-performance hosting platform optimized for Next.js. |

---

## 🚀 Getting Started

Follow these steps to set up and run the project locally.

### Prerequisites

* Node.js (LTS version recommended)
* npm or yarn

### Setup

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/yusufweb/AJO.git](https://github.com/yusufweb/AJO.git)
    ```

2.  **Navigate into the project directory:**
    ```bash
    cd ajo
    ```

3.  **Install dependencies:**
    ```bash
    npm install
    # or
    # yarn install
    ```

4.  **Set up Environment Variables:**
    Create a file named `.env.local` in the root directory and add your Firebase, Paystack, and Flutterwave credentials. *Consult the Digital Ajo contributor guide for a full list of required variables.*

5.  **Run the development server:**
    ```bash
    npm run dev
    # or
    # yarn dev
    ```

The platform will now be running on [http://localhost:3000](http://localhost:3000).

---

## 🗺 Future Plans

We have an ambitious roadmap to turn Ajo into a comprehensive financial inclusion platform.

* **Mobile App:** Develop a native mobile experience using **React Native**.
* **Credit Scoring:** Leverage contribution history to generate a proprietary credit score for members.
* **Integration:** Explore partnerships with insurance providers and formal cooperative bodies.
* **Trust Layer:** Implement a **Blockchain-powered trust layer** for immutable and verifiable group agreements.

---