# PlateWise
**Smart Restaurant Management System**

🔗 **Live App:** https://astounding-dragon-e8d219.netlify.app/
🔗 **GitHub Repo:** https://github.com/KawyashreeSenthilkumar/platewise-final

---

## Team Name
Kawyashree Senthilkumar (Solo participant)

---

## Problem We're Solving
Restaurants continue to rely on manual processes — customers don't know what's available, staff and kitchen communication is delayed, and orders/tables/billing are managed manually. PlateWise digitizes this entire workflow into one connected system for customers and restaurant staff.

---

## Tech Stack
- **Frontend:** HTML5, CSS3, JavaScript
- **Data Persistence:** Browser LocalStorage
- **Deployment:** Netlify
- **Version Control:** GitHub

*A lightweight, dependency-free architecture — chosen deliberately for fast iteration, zero setup overhead, and reliable deployment within the hackathon timeframe.*

---

## User Stories Completed

### ✅ Bronze Level — User Experience
- Modern, intuitive interface for both customers and restaurant staff, demonstrating clear digital improvement over manual restaurant operations.

### ✅ Silver Level — Authentication & Digital Operations
- Secure staff login restricted to a specific registered email and password
- Customer login (Email/Password) and a separate Google sign-in option (demo flow)
- Role-based access: separate Customer view and Staff/Manager view
- Digitized core workflows:
  - Digital menu with live item availability
  - Table booking/reservation system
  - Order management (place, accept, reject, prepare, ready)
  - Billing with payment method selection (Cash / UPI / Card)
  - Customer-facing notifications via live status updates

### ✅ Gold Level — Restaurant Management
- Manager dashboard covering:
  - **Orders** — live order queue with Accept/Reject/status progression
  - **Tables** — table booking requests with Confirm/Decline actions
  - **Inventory** — add new dishes, delete dishes, and toggle real-time availability, instantly reflected on the customer menu
  - **Sales/Analytics** — live KPIs: active orders, today's revenue, table count, sold-out item count

### ✅ Platinum Level — Intelligent Operations (Partial)
- "Recommended for you" smart suggestion banner using rule-based logic over item availability and popularity, demonstrating the intelligent-recommendation concept requested at this level.

---

## AI Usage
Claude (Anthropic), GitHub Copilot, and Google Antigravity were used as coding assistants throughout development — for scaffolding features, debugging, and iterative UI/UX refinement. The in-app "Recommended for you" feature uses rule-based logic (availability + popularity-weighted selection); this is planned for a future upgrade to a real AI recommendation model (e.g. Gemini API).

---

## Key Features
- 🍽️ Digital menu with live "Sold Out" / "Available" sync between staff and customer views
- 👨‍🍳 Staff can add or remove dishes directly from the dashboard, visible to customers instantly
- 🔒 Staff dashboard protected by a dedicated login (only authorized restaurant staff can access it)
- 📅 Table booking with staff confirm/decline
- 🛒 Cart and checkout with payment method selection
- 🧾 Full order lifecycle: Placed → Accepted/Rejected → Preparing → Ready
- 📊 Manager dashboard with live KPIs
- 💾 Persistent state via LocalStorage — works across page refreshes

---

## How to Run Locally
1. Download `index.html` from this repository
2. Double-click the file to open it directly in any modern browser
3. No installation, server, or build steps required

---

## Future Roadmap
- Real backend (Supabase/PostgreSQL) for true multi-device, multi-restaurant persistence
- Real-time sync via WebSockets instead of polling
- Integration with an actual AI model (Gemini API) for personalized recommendations and demand forecasting
- SMS/WhatsApp notifications for order and booking status
- Multi-language menu support (Tamil/Hindi/English)

---

## Hosted Application Link
https://astounding-dragon-e8d219.netlify.app/
