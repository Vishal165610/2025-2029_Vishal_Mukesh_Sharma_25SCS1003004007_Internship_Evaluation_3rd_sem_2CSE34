# Full Stack Development Internship – Vishal Mukesh Sharma

## Student Details

* **Name:** Vishal Mukesh Sharma
* **Roll No.:** 25SCS1003004007
* **Program:** B.Tech CSE
* **Semester:** 3rd Semester
* **Section:** 2CSE34
* **Organization:** Edurack (EdTech Startup)
* **Role:** Core Full Stack Developer
* **Live Website:** [www.edurack.in](https://www.edurack.in)

---

## Internship Overview

This repository contains the source code, documents, and supporting material from my internship at **Edurack**, an EdTech startup building CBT test simulators and a mentor marketplace for **NEET, JEE, CUET and IPMAT** aspirants.

I worked as the **core full stack developer** and was responsible for designing, building, and shipping the platform end to end, from the database and secure server-side logic to the student, mentor, promoter, intern, and admin interfaces. The platform is **live in production at [www.edurack.in](https://www.edurack.in)**.

The internship focused on building a real, revenue-ready product: authentication, payments, a computer-based test engine, video lectures, role-based dashboards, transactional email, and cloud storage.

---

## Projects and Modules Completed

### 1. Student Platform and CBT Test Engine
A computer-based test experience that mirrors real exam interfaces, with a question palette, timers, and answer marking. Access is re-verified on the server, grading is done server-side (correct answers and solutions are never sent to the browser before submission), and students get detailed result and subject-wise performance analysis. Includes a public CBT simulator and a live demo test for visitors.

### 2. Mentor Marketplace and Batch Hub
A unified batch and course hub where mentors run live batches and students learn from them. Includes a multi-step mentor onboarding wizard, lecture library with progress tracking and comments, mentor–student chat, announcements, notes, session scheduling, reviews, and mentor recommendations based on student weaknesses.

### 3. Payments and Commerce
A Razorpay integration in which prices are always looked up on the server, never trusted from the client. Payments are confirmed with HMAC-SHA256 signature verification before content is unlocked. Supports batches, bundles, test series, standalone tests, and mentor sessions, with automatic commission splits and purchase confirmation emails.

### 4. Authentication and Security
Firebase Authentication with server-side ID token verification, plus separate HMAC-signed session tokens for mentors and promoters. Includes email OTP verification (HMAC-SHA256 hashed with a server-side pepper, never stored in plaintext), secure password reset tokens, CSRF protection for server functions, timing-safe comparisons, per-device session tracking, and time-limited signed URLs for protected video content.

### 5. Admin Dashboard
A super-admin control panel for managing users, mentors, batches, bundles, tests, question ingestion, purchases, support tickets, promoter payouts, session templates, and intern applications.

### 6. Promoter (Affiliate) Portal
A separate portal for promoters to select batches to promote, track sales, request coupons and payouts, manage their profile, and raise support tickets.

### 7. Intern Hub
An internal intern management system with applications, trial assignments, task workspace, question draft submission and review, and auto-generated offer letters and certificates.

### 8. Media, Email and Infrastructure
Resumable multipart video uploads to AWS S3 delivered through CloudFront, image and document storage on Supabase, branded transactional emails through Resend, a caching layer for high-traffic public pages, SEO support (sitemap, structured data), legal pages (Terms, Privacy, Refund), and production deployment.

---

## Technologies and Tools

**Frontend**
* React with TypeScript
* TanStack Start, TanStack Router, and TanStack Query
* Tailwind CSS
* Radix UI and shadcn/ui components
* Recharts (analytics charts) and KaTeX (math rendering)

**Backend**
* TanStack Start server functions (Node.js)
* Server-side validation and role-based access control

**Database and Storage**
* MongoDB (Atlas)
* AWS S3 and CloudFront
* Supabase Storage

**Authentication and Security**
* Firebase Authentication and Firebase Admin SDK
* HMAC-signed session tokens
* Email OTP with hashed codes
* CSRF middleware
* Signed URLs

**Payments and Communication**
* Razorpay
* Resend (transactional email)

**Development and Deployment**
* Visual Studio Code
* Git and GitHub
* Vercel
* Browser testing and API testing

---

## Repository Contents

This repository includes:

* Internship Report
* Project Documentation
* Certificates and Supporting Documents
* Other internship-related files


**Project scale**

* 190+ source files and roughly 58,000 lines of TypeScript / TSX
* 35+ application routes
* 270+ server functions
* 45+ MongoDB collections

---

## Learning Outcomes

Through this internship, I gained practical experience in:

* Full stack development with React, TypeScript, and TanStack Start
* Designing and managing a MongoDB database
* Secure authentication and role-based access control
* Payment gateway integration and server-side verification
* Building a computer-based test engine with server-side grading
* Cloud storage, video delivery, and large file uploads
* Transactional email and OTP flows
* Performance optimization and caching
* Production deployment and debugging
* Taking a product from development to a live launch
* Working in a fast-paced startup environment

---

## Internship Organization

**Edurack**
Edurack is an EdTech startup that helps NEET, JEE, CUET and IPMAT aspirants practice with realistic mock tests, understand their weaknesses, and find the right mentor. The internship provided hands-on experience building and launching a real product used by real users.

---

## Student

**Vishal Mukesh Sharma**
Core Full Stack Developer, Edurack
Roll No. 25SCS1003004007

*This repository is created for academic and internship evaluation purposes.*
