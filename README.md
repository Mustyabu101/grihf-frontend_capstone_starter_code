# StayHealthy Frontend Development Capstone

## Project Overview

StayHealthy is a healthcare demonstration application developed
for the IBM Skills Network Frontend Development Capstone.

It provides patient registration, login, a patient dashboard,
doctor search, appointment requests and patient reviews.

## Application Repository

The completed application source code is available at:

https://github.com/Mustyabu101/med_appt

The application is developed on the
feature/secure-cookie-authentication branch.

This starter repository contains the capstone README.
The application source code and dependencies are maintained
in the med_appt repository.

## Technologies Used

- React and JavaScript
- Vite, HTML and CSS
- Vercel serverless functions
- Neon PostgreSQL
- JWT-based authentication

## Setup Instructions

### Prerequisites

- Node.js and npm
- Git

### Installation

Clone the application repository:

    git clone -b feature/secure-cookie-authentication https://github.com/Mustyabu101/med_appt.git

Enter the project directory:

    cd med_appt

Install dependencies:

    npm ci

Start the frontend development server:

    npm run dev

The local Vite development server does not automatically
provide the Vercel serverless API endpoints.

## Production Build

Run:

    npm run build

The frontend output is generated in the dist directory.

## Environment Variables

The deployed authentication and appointment services require:

- NEON_POSTGRES_URL
- JWT_SECRET

Never commit actual credentials or secrets.

## Project Limitations

Doctor listings are demonstration data.
Appointment requests do not represent confirmed bookings
with real medical professionals.

## Purpose

This project demonstrates frontend development,
authentication integration, and healthcare application
interface design for educational assessment.
