### 📊 Dashboard
- Live stats: active employees, team leaders, shifts this week, historical weeks
- Warning banners when shifts are missing a Team Leader
- Mini schedule overview for the current week
- Quick-action buttons for common tasks

### 👥 Employee Management
- Add/edit/deactivate/reactivate/permanently-delete employees
- Assign role (**Team Leader** ⭐ or **Employee**) and seniority level (1–5 ★)
- Full **shift history** per employee across all stored weeks
- Deactivated employees are preserved for history; only permanent delete removes them

### 📅 Schedule Builder
- **Week navigator** with ◀ Prev / Next ▶ / Today buttons
- **Create from Template**: auto-generates the full Sun–Sat shift grid using the 24/7 pattern:
  - **Sun–Thu**: Day (07:00–19:00) + Night (19:00–07:00) — regular workdays
  - **Thu night → Sat night**: marked as **Weekend shifts** (orange)
- **Copy Previous Week**: duplicates assignments from last week as a starting point
- Click any shift card → modal to:
  - Edit label, start/end times, weekend flag, notes
  - Assign/unassign employees via checkboxes (Team Leaders shown first with ⭐)
  - **Live warning** if no Team Leader is selected
  - **Conflict indicator** if an employee is already on another shift that same day

### 📋 Reports
- Generates a formatted, professional weekly schedule table
- **📸 Download as Image** — renders the report as a PNG file (via `html2canvas`) ready to send to team members
- **🖨️ Print** fallback using the browser's print dialog
- Reports show: day, date, shift type, hours, team leader, team members — with weekend rows highlighted

### ⚙️ Settings & Data Safety
- **Export Backup** → downloads a `.json` file with all employees + all week schedules
- **Import Backup** → restores from a previously exported file (merge)
- **Clear All Data** with a type-to-confirm safety gate
