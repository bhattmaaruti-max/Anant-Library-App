# Anant Library App

A responsive, front-end MVP for managing a study library. It includes an admin dashboard, a student portal, seat allocation, attendance, fee tracking, income reporting, profile photos, and local browser persistence.

## Run locally

```bash
npm install
npm run dev
```

Open the local URL shown by Vite. The demo sign-in PIN is `1234`.

## Included MVP workflows

- Add, edit, search, and delete student records with ID, phone, photo, seat, joining date, and monthly fee.
- Prevent duplicate seat selection while adding a student; view occupied and available seats.
- Record student entry and exit attendance and see live present counts.
- Enable the early-entry monitoring indicator and request browser location permission for attendance/location checks.
- Track paid and due fees, record a demo payment, view pending fees, monthly total, overall income, and a payment chart.
- Switch between admin and student portal views; browser storage retains demo records between refreshes.

## Production note

This repository intentionally ships as a front-end MVP. The PIN, session marker, browser storage, browser location request, attendance, and payment actions are demonstrations only. Production use requires a server-side identity provider, hashed passwords, role authorization, encrypted data storage, geofencing against an authoritative library location, tamper-resistant attendance records, notification delivery, and a payment gateway.
