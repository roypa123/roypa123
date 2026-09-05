# ✋ Roy P A

**`Flutter Developer`**

As a Flutter developer, I specialize in crafting immersive mobile experiences with a strong foundation in Dart programming. I thrive on the platform's promise of cross-platform efficiency, creating visually stunning and functionally robust applications.

My commitment to continuous learning drives me to stay updated with the latest Flutter advancements, ensuring that I deliver cutting-edge solutions. Collaborative by nature, I excel in team environments, leveraging my expertise to brainstorm creative solutions.

From conceptualization to deployment, I prioritize user experience, meticulously refining every aspect of my applications for optimal performance. I'm dedicated to pushing the boundaries of mobile app development and delivering impactful solutions.

---
### 🧰 Languages and Tools

<img align="left" alt="Git" width="30px" style="padding-right:10px;" src="https://github.com/devicons/devicon/blob/master/icons/flutter/flutter-original.svg" />
<img align="left" alt="Git" width="30px" style="padding-right:10px;" src="https://github.com/devicons/devicon/blob/master/icons/dart/dart-original.svg" />


<img align="left" alt="Git" width="30px" style="padding-right:10px;" src="https://github.com/devicons/devicon/blob/master/icons/postman/postman-original.svg" />
<img align="left" alt="Git" width="30px" style="padding-right:10px;" src="https://github.com/devicons/devicon/blob/master/icons/figma/figma-original.svg" />
<img align="left" alt="Git" width="30px" style="padding-right:10px;" src="https://github.com/devicons/devicon/blob/master/icons/jira/jira-original.svg" />
<img align="left" alt="Git" width="30px" style="padding-right:10px;" src="https://github.com/devicons/devicon/blob/master/icons/bitbucket/bitbucket-original.svg" />
<img align="left" alt="GitHub" width="30px" style="padding-right:10px;" src="https://github.com/devicons/devicon/blob/master/icons/git/git-original.svg" />
<img align="left" alt="GitHub" width="30px" style="padding-right:10px;" src="https://github.com/devicons/devicon/blob/master/icons/vscode/vscode-original.svg" />



<br />

# My Projects Portfolio

Welcome to my Flutter projects portfolio! Below you'll find a collection of projects I've worked on using Flutter.



##  Company Projects

### Tele2

Tele2 is a telecommunications company that provides mobile, broadband, and digital communication services. The Tele2 project/portal can be described as a platform designed to support and manage telecom services, customers, sales, and related business operations.

Important package used:

1. React
2. Tailwind
3. Shadcn/ui
4. Redux tool kit
5. Nx Monorepo

### STC

STC (Saudi Telecom Company) is a leading telecommunications and digital services provider offering mobile, internet, cloud, cybersecurity, and digital solutions. It helps connect individuals and businesses through advanced technology and communication services.

Important package used:

1. React
2. Tailwind
3. Shadcn/ui
4. Redux tool kit
5. Nx Monorepo

### Toffeeride 

An intelligent platform to promote self-learning in children . An app based solution accessible on your smartphones, tablets, laptops, and desktops

Important Packeges used

 1. Flutter
 2. Getx
 3. http


### Just Borrow

A user-friendly and comprehensive rental platform that simplifies the process of finding and renting a wide range of items, properties, and services.

Important Packeges used

 1. Flutter
 2. Getx
 3. http

### Quotely

A motivation app that delivers daily inspirational quotes, empowering users with positivity. It features categorized quotes, a sleek design, and sharing options to uplift and inspire anytime, anywhere.

Important Packeges used
 
 1. Flutter
 2. Getx
 3. http
 



### Tori

Tori is a storytelling app for children, bringing stories to life with immersive background music and sound effects. It offers an engaging, audio-visual experience
to captivate young minds and enhance learning

Important Packeges used
 
 1. Flutter
 2. Provider
 3. Dio
 4. GetIt






##  My Projects

### Nexlytics

Nexlytics is a self-hosted, privacy-conscious web analytics platform — a lighter, more transparent alternative to Google Analytics, built for teams who want first-party visibility into their website traffic without third-party data sharing.

At its core, Nexlytics tracks visitor behavior through a lightweight JavaScript snippet embedded on a customer's website. It automatically captures pageviews, sessions, and referrer chains, and exposes a simple window.nexlytics(name, props) API for custom event tracking — clicks, form submissions, conversions, anything a site owner wants to measure. Events flow through a dedicated, publicly reachable collector service, designed to accept traffic from any origin without requiring authentication, since it's meant to be embedded on strangers' websites.


1. React
2. Tailwind
3. Shadcn/ui
4. TanStack Query/Router,
5. Jotai,
6. FastAPI
7. PostgreSQL
8. Docker
9. Dokploy



<img 
  src="https://raw.githubusercontent.com/roypa123/analytics/main/image/landing_page.jpg"
  width="1000"
  height="576"
  alt="Dashboard"
/>

<img 
  src="https://raw.githubusercontent.com/roypa123/analytics/main/image/dashboard.JPG"
  width="1000"
  height="576"
  alt="Dashboard"
/>

<img 
  src="https://raw.githubusercontent.com/roypa123/analytics/main/image/realtime.JPG"
  width="1000"
  height="576"
  alt="Dashboard"
/>

 Repository: [Nexlytics](https://github.com/roypa123/analytics)

 ### Aura Health — Hospital Management System

Aura Health is a full-stack hospital management platform built to run the day-to-day operations of a multi-department clinical facility, from patient registration through billing and insurance claims. The backend is a Node.js/Express REST API backed by PostgreSQL (via Knex), with a React 19 + TypeScript single-page frontend styled with Tailwind and shadcn/ui components.

The system models nine distinct roles — Admin, Doctor, Receptionist, Nurse, Lab Technician, Pharmacist, Cashier, Insurance Officer, and Patient — enforced through a hybrid RBAC/ABAC layer that combines exact role checks with a numeric role-priority hierarchy, so senior roles inherit access without needing every permission explicitly listed. Authentication uses JWT access tokens paired with database-tracked refresh tokens, optional TOTP-based two-factor authentication with backup codes, and per-device session management.

Core clinical workflows include appointment scheduling with optimistic-locking slot booking to prevent double-bookings, electronic medical records, digitally-signed prescriptions, pharmacy inventory managed on a first-expiry-first-out basis, and diagnostic lab test tracking. A unified "checkout" transaction ties a consultation together in one atomic step — recording the diagnosis, issuing a prescription, ordering labs, and generating an itemized invoice — with Razorpay integration for online payments and support for insurance claims against patient policies.

Supporting infrastructure includes MinIO object storage for medical document uploads, Redis-backed background job queues (BullMQ) for email delivery and audit logging, real-time Socket.IO notifications pushed to patients and staff, and a full audit trail of sensitive actions across the system. The application is containerized with Docker and deployed via Dokploy, with Postgres, Redis, and MinIO running as independent managed services.

The result is a realistic, production-shaped reference implementation of hospital operations software — useful both as a working clinic management tool and as a demonstration of layered backend architecture (routes → controllers → services → repositories), role-based access control design, and transactional business logic in a healthcare domain.

1. React
2. Tailwind
3. Shadcn/ui
4. TanStack Query/Router,
5. zustand,
6. Node.js
7. PostgreSQL
8. Redis
9. MinIO
10. Docker
11. Dokploy



<img 
  src="https://raw.githubusercontent.com/roypa123/analytics/main/images/login.JPG"
  width="1000"
  height="576"
  alt="login"
/>

<img 
  src="https://raw.githubusercontent.com/roypa123/analytics/main/images/dashboard.JPG"
  width="1000"
  height="576"
  alt="Dashboard"
/>

<img 
  src="https://raw.githubusercontent.com/roypa123/analytics/main/images/appointment_scheduler.JPG"
  width="1000"
  height="576"
  alt="appointment-scheduler"
/>

<img 
  src="https://raw.githubusercontent.com/roypa123/analytics/main/images/pharmacy_stock.JPG"
  width="1000"
  height="576"
  alt="Pharmacy_stock"
/>

<img 
  src="https://raw.githubusercontent.com/roypa123/analytics/main/images/profile_settings.JPG"
  width="1000"
  height="576"
  alt="Profile_settings"
/>



Repository: [Aura Health](https://github.com/roypa123/hospital)


### Weather App

A Weather App is a mobile application designed to provide users with accurate, real-time weather information. It offers a convenient way to stay updated on current weather conditions, helping users plan their daily activities accordingly.

Important Packeges used

 1. Flutter Bloc
 2. Dio
 3. GetIt
 4. geolocator

 <img src="https://github.com/roypa123/weather_app/blob/9bb4c65a6b769bf2740dc7f532dafee6e71ce8aa/extrafile/git_images/image1.jpeg" width="225.8" height="500"/> 

 Repository: [Weather-App](https://github.com/roypa123/weather_app)

________________________________________


###  FLASHLIGHT

Description: A flashlight app is a simple yet highly useful utility application that allows users to use their device as a source of light. These apps utilize the device's built-in LED flash (usually associated with the camera) or the screen to provide illumination. Flashlight apps are essential tools for various scenarios, from finding items in the dark to providing light during power outages.

state mangement: BLOC

|  <img src="https://github.com/roypa123/flashlight/blob/27b0b7a64f7644b33a416d1b1ec26edf16e96973/extra_file/git_images/image1.jpeg?raw=true" width="225.8" height="500"/>  |  <img src="https://github.com/roypa123/flashlight/blob/27b0b7a64f7644b33a416d1b1ec26edf16e96973/extra_file/git_images/image2.jpeg?raw=true" width="225.8" height="500"/>   |   <img src="https://github.com/roypa123/flashlight/blob/27b0b7a64f7644b33a416d1b1ec26edf16e96973/extra_file/git_images/image3.jpeg?raw=true" width="225.8" height="500"/>

Repository: [flash-light](https://github.com/roypa123/flashlight)

________________________________________


### BMI CALCULATOR

Description: A BMI Calculator App is a user-friendly tool designed to help individuals assess their Body Mass Index (BMI) conveniently. It provides insights into whether a person is underweight, normal weight, overweight, or obese based on their height and weight

state mangement: BLOC

|  <img src="https://github.com/roypa123/bmicalculator/blob/cbe2de6ccfd1def487a11dc4d28db43f7adb188e/extra_file/git_images/image1.jpeg" width="225.8" height="500"/>   |   <img src="https://github.com/roypa123/bmicalculator/blob/cbe2de6ccfd1def487a11dc4d28db43f7adb188e/extra_file/git_images/image2.jpeg" width="225.8" height="500"/>   |   <img src="https://github.com/roypa123/bmicalculator/blob/cbe2de6ccfd1def487a11dc4d28db43f7adb188e/extra_file/git_images/image3.jpeg" width="225.8" height="500"/>

Repository: [bmi-calculator](https://github.com/roypa123/bmicalculator)

________________________________________


### CALCULATOR

A Calculator App is a versatile and user-friendly application designed to perform mathematical calculations efficiently. Whether you're solving simple arithmetic problems or tackling complex equations, a calculator app provides a convenient and portable solution. 

state management

BLOC

|  <img src="https://github.com/roypa123/calculator/blob/2a04885241ecf7be49b721bd5b2364cb992711d2/extra_file/git_images/image1.jpeg" width="225.8" height="500"/>   |   <img src="https://github.com/roypa123/calculator/blob/2a04885241ecf7be49b721bd5b2364cb992711d2/extra_file/git_images/image2.jpeg" width="225.8" height="500"/>  

Repository: [calculator](https://github.com/roypa123/calculator)
________________________________________


## About Me

I'm a passionate Flutter developer with experience building cross-platform mobile applications. I enjoy creating intuitive and visually appealing user interfaces using Flutter's rich set of widgets.

## Contact

Contact me via email at [roypa81130@gmail.com](mailto:roypa81130@gmail.com).














