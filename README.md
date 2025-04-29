# welcome-screen

A real-time welcome screen system developed to display visitor information upon successful QR code scanning at event check-in points.  
This screen is **linked to the QR scanning page** via a broadcast channel, allowing it to update automatically based on scan status.

## Overview

The welcome screen dynamically updates to show specific guest details (such as name, unit number, or ticket information) based on real-time status updates from the QR scanning system.

### Key Features

- **Real-Time Status-Driven Display**
  - Displays live scan results instantly without manual refresh
  - Shows guest details such as name and unit/ticket info upon successful check-in

- **Duplicate Check-In Prevention**
  - Prevents re-entry by checking for duplicate scans
  - Ensures accurate and secure event check-in

- **Event-Friendly Design**
  - Optimized for large screens or projections at entrances
  - Provides clear visual confirmation for both guests and staff

### Use Case

The screen is typically placed at venue entrances to visually confirm successful check-in. It enhances the event experience with real-time feedback and supports smooth crowd control.

### Contributions

- Designed and implemented the visual layout of the welcome screen
- Customized the fields displayed based on scan results received from the backend
- Integrated logic to detect and display duplicate check-in attempts
- Ensured a clean, responsive design suitable for large-screen event use

### Watch Demo
- [AUG's 30th Anniversary Dinner](https://youtu.be/K9340iq0zy8)
