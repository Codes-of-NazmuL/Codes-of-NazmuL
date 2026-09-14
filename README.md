<p align="center">
  <img src="https://raw.githubusercontent.com/Codes-of-NazmuL/Codes-of-NazmuL/main/cover.png" alt="Nazmul Islam — Flutter Developer" width="100%" />
</p>

<h1 align="center">Nazmul Islam</h1>

<p align="center">
  <strong>Flutter Developer</strong><br/>
  Building mobile products around real workflows, API integrations, AI-assisted features, payments, messaging, and platform-specific behavior.
</p>

<p align="center">
  <a href="https://nazmuls.app">
    <img src="https://img.shields.io/badge/Portfolio-nazmuls.app-111111?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" />
  </a>
  <a href="https://www.linkedin.com/in/nazmul-islam-qnix">
    <img src="https://img.shields.io/badge/LinkedIn-Nazmul_Islam-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:nazmulislambd2004@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact_Me-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

---

## About Me

I am a Flutter developer focused on building production mobile applications rather than isolated demo screens.

Most of my work involves taking a real product requirement, understanding the workflow behind it, and turning it into a mobile experience that can handle API state, authentication, payments, messaging, deep links, local persistence, and platform-specific behavior.

I have worked on healthcare applications, anonymous social products, QR-based ownership and recovery systems, rental marketplaces, AI-assisted clinical workflows, and team-management products.

I care about keeping the codebase understandable, handling edge cases properly, and making the application behavior match the real-world process behind the product.

---

## What I Work With

### Mobile

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square\&logo=flutter\&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square\&logo=dart\&logoColor=white)

### State & Local Data

![GetX](https://img.shields.io/badge/GetX-8A2BE2?style=flat-square\&logo=flutter\&logoColor=white)
![Provider](https://img.shields.io/badge/Provider-4479A1?style=flat-square\&logo=flutter\&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=flat-square\&logo=sqlite\&logoColor=white)
![GetStorage](https://img.shields.io/badge/GetStorage-4DB6AC?style=flat-square)

### APIs, Services & Delivery

![REST API](https://img.shields.io/badge/REST_API-222222?style=flat-square\&logo=json\&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square\&logo=firebase\&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square\&logo=docker\&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square\&logo=nginx\&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square\&logo=git\&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square\&logo=github\&logoColor=white)

**Also worked with:** REST integrations, Firebase services, Stripe payment flows, deep linking, passkey-based authentication flows, push notifications, chat systems, AI-generated structured data, and mobile app release workflows.

---

## Selected Work

> Some of these are client projects, so the source code is private. I describe the engineering work rather than linking to code I cannot publish.

### Chaizen — Anonymous Social App

An anonymous social application built around interactive floating bubbles and chat.

I worked on the bubble interaction, including randomized movement to avoid a repetitive animation pattern, and on the identity flow. An early device-ID approach was not reliable enough on iPhone, so the authentication model moved toward passkeys to keep a persistent identity without introducing a traditional username/password login flow.

**Worked on:** `Flutter` `Animation` `Authentication` `Passkeys` `Chat`

---

### Mojacares — Healthcare Service App

A healthcare platform connecting patients, staff, service orders, medical reports, recorded health vitals, AI insights, and AI chat.

The interesting part was not simply displaying health data. Patient information could come from uploaded reports as well as staff-recorded vitals after a service. The mobile experience then had to present that processed information clearly, including health scores and visual states for different parts of the health summary.

**Worked on:** `Flutter` `Patient Workflows` `Staff Workflows` `AI Insights` `AI Chat`

---

### Mediscribe AI — AI-Assisted Clinical Notes

A mobile workflow for recording doctor-patient consultations and turning the processed conversation into structured SOAP notes: Subjective, Objective, Assessment, and Plan.

The recording is uploaded after the consultation, processed by AI, and converted into a structured clinical note that can remain in the patient's history.

The useful part was not the recording itself, but turning a natural conversation into information a doctor could review without starting the documentation from scratch.

**Worked on:** `Flutter` `Audio Recording` `AI Processing` `SOAP Notes` `Patient History`

---

### COOW — QR Ownership & Recovery Platform

COOW started as what looked like a QR scanner, but the actual product was much broader.

QR codes could be attached to vehicles, personal items, products, or company-managed resources.

The app supported deep-link routing, lost mode, owner/finder messaging, reward negotiation, verification-based account levels, and company accounts where multiple users could manage shared QR resources.

**Worked on:** `Flutter` `QR Scanning` `Deep Linking` `Messaging` `Account Verification` `Role-Based Access`

---

### Adventure Rentals — Vehicle Rental Marketplace

A two-sided rental marketplace for sports vehicles.

Providers can list vehicles and renters can review specifications and pickup information, send booking requests, communicate with the provider, and continue through the rental lifecycle after approval.

The application also includes chat and a Stripe-based escrow-style payment flow tied to the booking process.

**Worked on:** `Flutter` `Marketplace Flow` `Booking State` `Chat` `Stripe`

---

### Gaelic Football Fantasy — Team Management

A team-building and player-management application for Gaelic football, a sport I had not worked with before this project.

The main challenge was learning the domain well enough to translate the client's team-management rules into the application.

Coaches could build teams around player budgets, positions, availability, injury status, performance information, and prediction-related features.

**Worked on:** `Flutter` `Team Building` `Budget Logic` `Player Management` `Domain-Driven UI`

---

## Public Repositories

A lot of my commercial work cannot be published publicly, but I keep practice projects and other public code on GitHub.

<p align="center">
  <a href="https://github.com/Codes-of-NazmuL?tab=repositories">
    <img src="https://img.shields.io/badge/Browse_All_Repositories-181717?style=for-the-badge&logo=github&logoColor=white" alt="Browse repositories" />
  </a>
</p>

---

## How I Think About Development

I usually start by understanding the actual workflow before choosing how to implement it.

A requirement that sounds simple on paper can hide state, permission, identity, payment, or platform-specific problems once development starts.

A few things I pay attention to:

* Keep UI state and business state predictable.
* Treat authentication and identity as separate problems when they are not actually the same thing.
* Design around failure cases, not only the happy path.
* Keep API contracts structured enough for the UI to make reliable decisions.
* Avoid rebuilding existing parts of a product unless there is a clear reason to do it.
* Test behavior on the real target platform instead of assuming Android and iOS behave the same way.

---

## Currently Exploring

I am continuing to deepen my work around AI/ML while keeping mobile engineering as my main development background, especially where AI features need to fit into real product workflows rather than exist as isolated demos.

---

## Connect

<p align="center">
  <a href="https://nazmuls.app">Portfolio</a>
  &nbsp;•&nbsp;
  <a href="https://www.linkedin.com/in/nazmul-islam-qnix">LinkedIn</a>
  &nbsp;•&nbsp;
  <a href="mailto:nazmulislambd2004@gmail.com">Email</a>
  &nbsp;•&nbsp;
  <a href="https://github.com/Codes-of-NazmuL?tab=repositories">Repositories</a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Codes-of-NazmuL&label=Profile%20Views&color=0e75b6&style=flat" alt="Profile Views" />
</p>
