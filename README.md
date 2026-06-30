# FlowBank-UI

**Premium Bank Queue Management -- Mobile UI Prototype**

[![Status](https://img.shields.io/badge/status-prototype-yellow)](https://github.com/tj193/FlowBank-UI)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License](https://img.shields.io/badge/license-MIT-blue)](LICENSE)

---

## Project Overview

**FlowBank-UI** is a front-end UI prototype for a premium banking queue management system. It simulates the mobile customer experience of selecting a banking service, receiving a digital ticket, tracking live queue status, and reviewing visit history -- all within a polished, mobile-first interface.

The prototype consists of four standalone HTML screens designed with a luxury banking aesthetic (navy and gold palette). Each page is fully self-contained with embedded CSS and JavaScript, requiring no build tools or server to render.

---

## Tech Stack & Libraries

| Layer | Technology |
|-------|-----------|
| **Markup** | HTML5 |
| **Styling** | CSS3 (vanilla, responsive, custom properties) |
| **Interaction** | JavaScript (vanilla, ES6) |
| **Typography** | Google Fonts -- Playfair Display, Inter (via CDN) |
| **Icons** | Native Unicode System Icons (No external font or bandwidth overhead) |
| **Design** | Mobile-first, touch-optimized, CSS animations |

**No front-end frameworks, no backend, no database, no NuGet packages, and no build tooling** are used in this project.

---

## Project Structure
FlowBank-UI/
├── 01-service-selection.html     # Service selection landing page
├── 02-notifications-setup.html   # Notification method and phone input
├── 03-queue-status.html          # Live ticket status and queue progress
├── 04-visit-history.html         # Visit history and active session review
└── README.md                     # Project documentation

All files reside at the root level. There are no subdirectories for assets, styles, or scripts because each page is self-contained.

---

## Screens & Implemented Features

### Screen 1 -- Service Selection
[Live Demo](https://tj193.github.io/FlowBank-UI/01-service-selection.html)

- Branded header with bank logo and branch location indicator
- Premier Queue System badge
- Three service cards (Teller Services, Account Services, Loans and Finance)
- "Recommended" card with accent styling and estimated wait times
- "Available Now" status indicator for walk-in-ready services
- Sticky bottom CTA ("Get Your Ticket")
- Animated card entrance (fade-in-up staggered)

### Screen 2 -- Notifications Setup
[Live Demo](https://tj193.github.io/FlowBank-UI/02-notifications-setup.html)

- Multi-step stepper (visual progress indicator)
- Mobile phone number input with country code selector (Iraq +964)
- Three notification method cards -- WhatsApp (recommended), SMS (traditional), In-Browser (live update)
- Selection toggle with checkmark indicator
- Consent disclaimer notice
- Sticky confirmation CTA ("Confirm and Generate Ticket")

### Screen 3 -- Queue Status
[Live Demo](https://tj193.github.io/FlowBank-UI/03-queue-status.html)

- Active ticket banner with queue number display (e.g., A-15)
- Progress bar animation
- Assigned service window display (e.g., Private Booth 04)
- Action buttons -- "Status: On Standby" / "Notify Me"
- Live queue progress card (currently serving and up next)
- Estimated wait time with circular progress indicator (SVG ring)
- "Persons ahead" count display
- Cancel ticket button with red styling
- Ticket reference and branch status footer

### Screen 4 -- Visit History
[Live Demo](https://tj193.github.io/FlowBank-UI/04-visit-history.html)

- Active session card with ticket ID, client type, service category, and check-in time
- Priority Client badge
- Completed visits list with history items showing service type, ticket number, and date
- Per-item status badges (Completed / Cancelled)
- Language selector button (EN)
- Encrypted archive footer message

---

## Setup & Installation

No build system, package manager, or server is required. To run the prototype:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/tj193/FlowBank-UI.git](https://github.com/tj193/FlowBank-UI.git)
   cd FlowBank-UI
Open the startup screen in a browser:

Bash
# Windows
start 01-service-selection.html

# macOS
open 01-service-selection.html

# Linux
xdg-open 01-service-selection.html
Alternatively, double-click the 01-service-selection.html file in your file manager.

Note: There is no backend, database, connection string, or migration step. The screens are static HTML prototypes and will not persist data or make network requests.

License
Distributed under the MIT License. See LICENSE for more information.
