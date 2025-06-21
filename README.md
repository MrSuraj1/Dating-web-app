# ❤️ LoveConnect – Dating Web App

**LoveConnect** is a full-featured dating and friend-finder web app built with Firebase and Tailwind CSS. It includes features like profile signup, matchmaking feed, "Rent a Girlfriend", real-time chat, and an admin booking panel — all powered by Firebase Authentication, Firestore, Realtime Database, and Storage.

---

## 🚀 Features

### ✅ Authentication
- Firebase Email & Password Auth
- User signup with photo upload
- Authenticated route protection

### 👤 User Profile
- Name, Email, Gender, DOB, Profile Photo
- Saved in Firestore under `/users/{uid}`

### 🏠 Dashboard
- Displays logged-in user's info
- Navigation to:
  - Feed
  - Rent a Girlfriend
  - Booked Profiles
  - Logout

### 💕 Feed Page
- Shows user cards (marriage/friendship)
- Male users only see female profiles
- Profiles fetched from Firestore

### 💘 Rent a Girlfriend
- Only male users can rent
- Fixed price: `$20`
- Clicking "Rent" saves booking in Firebase Realtime DB under `/bookings/`

### 💬 Realtime Chat
- Starts from profile page
- Messages stored in Firestore under `/chats/{chatId}/messages`

### 🔐 Admin Panel
- View all bookings
- See renter (male) and rented (female) info
- Realtime database integration

---

## 🔥 Built With

- **HTML5** + **Tailwind CSS**
- **Vanilla JavaScript**
- **Firebase:**
  - Auth
  - Firestore
  - Realtime Database
  - Storage

---

## 📁 Project Structure

📦 LoveConnect/
├── index.html # Login
├── signup.html # Signup form
├── dashboard.html # Main dashboard
├── feed.html # Matchmaking feed
├── profile.html # View full profile + chat
├── chat.html # Realtime chat
├── rent.html # Rent a GF
├── booked.html # View booked GF
├── admin.html # Admin view
└── error.html # Error fallback


---

### ✅ Next steps:

- Replace `YOUR_USERNAME` with your GitHub username.
- Add screenshot links if needed (`![Screenshot](path)`).
- Create `README.md` file in your root folder and paste the code above.

Let me know if you want the **README in downloadable `.md` format** or want me to create the GitHub repo structure for you.
