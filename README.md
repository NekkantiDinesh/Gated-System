# The Gatehouse Register 🛡️🏠

A lightweight, dual-interface visitor management prototype designed to simulate real-time coordination between gated community security (watchman) and residents.

---

## 🌟 Overview

**The Gatehouse Register** demonstrates a two-screen synchronization workflow within a single interactive dashboard:

1. **Watchman Interface (Gatehouse App):** Allows security personnel to select an apartment unit, specify visitor categories (couriers, food delivery, guests, cabs), add notes, and log arrivals.
2. **Resident Interface (Owner App):** Enables residents to view waiting visitors, grant entry approvals, and pre-approve expected visitors in advance.

---

## ✨ Features

- **Dual-View Simulation:** Side-by-side view of both security guard and resident mobile screens on a single page.
- **Pre-Approval System:** Residents can pre-register incoming visitors; security receives instant auto-clearance options upon visitor arrival.
- **Real-Time Status Tracking:** Immediate visual updates for pending, approved, and pre-approved entry logs.
- **Wing & Room Management:** Organized room directory broken down by Wing and Apartment numbers.
- **Zero Dependencies:** Pure vanilla HTML, CSS, and JavaScript with no external framework dependencies.

---

## 🚀 Quick Start

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/gatehouse-register.git](https://github.com/your-username/gatehouse-register.git)



Open the application:
Simply double-click gated system.html (or open it directly in any modern web browser). No local server, build process, or npm install required.
🛠️ Built WithHTML5   CSS3 (Flexbox, Grid, Custom CSS Variables)   Vanilla JavaScript (State-driven DOM rendering, Event Delegation)   Google Fonts (Space Grotesk, Inter, Space Mono)
📝 Usage GuidePre-approve a visitor (Resident side):Select your room number from the drop-down on the right screen[cite: 1].Click "Expecting someone? Let the watchman know"[cite: 1].Choose visitor type, add optional details, and click Send to watchman[cite: 1].Log an arrival (Watchman side):Select the target room and visitor type on the left screen[cite: 1].If pre-approved, click Let them in — already approved[cite: 1].Otherwise, click Notify room to send an instant entry request to the resident screen[cite: 1].Approve entry (Resident side):View pending gate notifications under AT THE GATE NOW[cite: 1].Click Approve and let them in[cite: 1].
