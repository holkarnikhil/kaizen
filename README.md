# KAIZEN (改善) — AI-Based Personal Life Assistant

A full-featured personal productivity and life assistant web application built with **React 19**, **Vite 8**, **Tailwind CSS**, and **Lucide Icons**, styled in an elegant **Beige & Gold** luxury aesthetic.

---

## 🎨 Theme & Aesthetic: Beige and Gold
- **Base Canvas:** Warm Ivory (`#FBF9F4`) and Soft Cream (`#FFFFFF`, `#FCF9F3`)
- **Accents:** Imperial Gold (`#C5A059`), Champagne Silk (`#DFCA95`), and Deep Burnished Bronze (`#9E7D3B`)
- **Typography:** Playfair Display (Serif Elegance) & Plus Jakarta Sans (Clean Modern Readability)

---

## 🏛️ Comprehensive Architecture & 17 Application Screens

| No. | Screen | Specification Reference | Features & ER Entities |
|---|---|---|---|
| 1 | **Sign In** | Section 4 (FR-02) | Secure authentication, role validation, 1-click Demo accounts for User & Admin |
| 2 | **Registration** | Section 4 (FR-01) | User registration (User ID, Name, Email, Phone, Password) |
| 3 | **Dashboard** | Section 22 Screen 3 | Central cockpit, 4 KPI cards, Procrastination alert banner, AI suggested slot, habit check-in, schedule preview |
| 4 | **User Profile** | Section 4 (FR-03, FR-04) | View/Edit profile, change password form, personal stats & achievement metrics |
| 5 | **Tasks** | Section 5 (FR-05) | Task CRUD, **Smart Task Priority Entity** (Reason & Update), **Procrastination Analysis Entity**, performance gauge |
| 6 | **Vice Tasks** | Section 6 (FR-06) | Manage vice tasks, triggers, replacement actions, abstinence streak counter, resisted urges log |
| 7 | **Reminders** | Section 7 (FR-07) | Reminder management, urgency levels, audio chime test trigger, repeat cadences |
| 8 | **Daily Planner** | Section 8 (FR-08) | Date & time slots, Task ID association, **AI Suggest** entity attributes, 1-click AI Auto-Plan |
| 9 | **Habit Tracking** | Section 9 (FR-09) | 7-day consistency interactive matrix, habit strength gauge (0-100%), cue & reward loops |
| 10 | **Expenses** | Section 10 (FR-10) | Personal expense tracking, category distribution chart, monthly budget utilization, Admin view/edit |
| 11 | **Activity History**| Section 11 (FR-11) | Real-time audit trail directly linked to **User Behaviour Analysis** model |
| 12 | **Notifications** | Section 12 (FR-12) | Notification center, delivery preferences, read/unread management, test alert dispatcher |
| 13 | **AI Suggestions** | Section 15, 16, 17, 18, 19 | Interactive AI Services hub, **User Behaviour Analysis**, Smart Priority & Procrastination breaker |
| 14 | **Reports** | Section 14 (FR-13) | Multi-dimensional productivity index, task status distribution, CSV export, print-ready layout |
| 15 | **Voice Task** | Section 20 (FR-16) | Web Speech API speech-to-text, audio waveform visualizer, intent parsing, Voice Task Entry entity store |
| 16 | **Settings** | Section 13 | Theme palette selection, daily morning & evening anchors, AI sensitivity thresholds |
| 17 | **Admin Dashboard**| Section 21, 24 (FR-17, 18)| User management table, global task ledger, system settings, **Backup & Restore Data (JSON Export/Import)** |

---

## 🚀 How to Run the Application

The application is already running in your development environment:

```bash
cd "kaizen-app"
npm run dev
```

Visit: **`http://localhost:5173/`**

### Pre-configured Demo Accounts:
- **Regular User:** Alex Vance (`alex.vance@kaizen.ai` / password: `password123`)
- **System Admin:** Master Admin (`admin@kaizen.ai` / password: `adminpassword`)
*(Use the convenient role switcher in the top navigation bar or the 1-click demo login buttons in the Sign In modal).*
