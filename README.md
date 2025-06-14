# ➤ DocNode – Real-Time Doctor Appointment Platform

**DocNode** is a Full Stack Telemedicine Platform that enables real-time consultations between doctors and patients from anywhere in the world. Built with cutting-edge technologies like **Next.js**,**Neon**, **Prisma**, **TailwindCSS**, **Shadcn UI**, and **Vonage** for secure video calling.

> ➤ Seamlessly book appointments, manage roles, conduct video calls, and handle subscriptions – all in real time.

---

## ➤ Live Demo

🔗 [Visit Live Site](https://your-live-site-link.com)  
📦 [View GitHub Repo](https://github.com/your-username/docnode)

---

## ➤ Preview

![DocNode Preview](https://your-image-link.com/docnode-preview.png)

---

## ➤ Tech Stack

| Frontend              | Backend          | Database       | Real-Time / Tools       |
|-----------------------|------------------|----------------|--------------------------|
| Next.js (App Router)  | API Routes (Next.js) | PostgreSQL / Supabase | Vonage (Video Calls)     |
| TailwindCSS           | Prisma ORM       | PlanetScale     | Stripe (Subscriptions)   |
| Shadcn UI             | JWT / Auth Logic |                | Clerk / Auth.js (Optional) |

---

## ➤ Features

### ➤ Real-Time Functionality
➡️ Appointment availability updates in **real time**  
➡️ Real-time **video call joining** and live session UI  

### ➤ Authentication & User Roles
➡️ Register as a **Doctor** or **Patient**  
➡️ Role-based access with protected dashboards  
➡️ Admin approval flow for doctor accounts  

### ➤ Doctor Discovery & Booking
➡️ Search doctors by **specialty**  
➡️ Browse real-time **slot availability**  
➡️ Book and manage appointments with ease  

### ➤ Appointment & Consultation System
➡️ Patients: View, cancel, or **join video calls**  
➡️ Doctors: Set availability, monitor earnings, accept calls  

### ➤ Video Calling (Vonage Integration)
➡️ In-browser secure consultations  
➡️ Controls for **mute/unmute**, **video toggle**, **end call**

### ➤ Subscription Management
➡️ Patients can purchase monthly plans or credits  
➡️ Admins can **review & process withdrawal requests**

### ➤ Dashboards
➡️ **Doctor Dashboard:** Availability, Calls, Earnings  
➡️ **Admin Dashboard:** Doctor verification & payment handling  

### ➤ Fully Responsive UI
➡️ Built with **TailwindCSS** and **Shadcn UI**  
➡️ Seamless user experience across all devices  

---

## ➤ Local Setup Instructions

```bash
# Navigate to your desired location
cd C:\Users\DELL\Desktop\Projects

# Clone the repository
git clone https://github.com/your-username/docnode.git
cd docnode

# Install project dependencies
npm install

# Set up environment variables
cp .env.example .env

# Generate Prisma client
npx prisma generate

# Start the development server
npm run dev
