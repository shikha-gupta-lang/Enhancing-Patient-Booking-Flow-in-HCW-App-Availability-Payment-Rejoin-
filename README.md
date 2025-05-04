# Enhancing-Patient-Booking-Flow-in-HCW-App-Availability-Payment-Rejoin-



---

### 📝 **Description:**

This PR adds three key features to the patient consultation flow in the HCW app, built using the **Ionic Framework** for both web and mobile platforms:

---

### 🔹 **1. Practitioner Availability (#43):**

* Integrated a calendar/date-picker allowing patients to view doctor availability in real-time.
* Used Ionic UI components to show available time slots dynamically fetched from the backend.
* Ensured smooth UX for selecting preferred consultation time.

---

### 🔹 **2. Payment Integration Before Booking Confirmation (#44):**

* Added a secure payment screen in the consultation booking flow.
* Integrated \[Razorpay/Stripe] (choose one depending on what you used).
* Booking is only confirmed after successful payment; failures are handled gracefully.

---

### 🔹 **3. Rejoin Ongoing Consultation from Dashboard (#45):**

* Implemented a “Rejoin” button on the dashboard for active consultations.
* Automatically checks consultation status via API.
* If ongoing, it allows patients to re-enter the virtual room using a magic link.

---

### 📱 **Tech Stack Used:**

* **Frontend:** Ionic Framework (HTML, CSS, TypeScript)
* **Backend APIs:** REST (for fetching availability, updating booking, processing payment, etc.)
* **Payment Gateway:** Razorpay / Stripe (as applicable)

---

### ✅ **Features Tested On:**

* iOS Emulator
* Android Device
* Web Browser (Responsive view)

---

### 🔐 **Security & Access Control:**

* Only authenticated patients can view their own consultations and perform bookings.
* Magic link/token system ensures secure access to consultation rooms.

---
