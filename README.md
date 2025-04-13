# Startup Operations Dashboard

A responsive, minimalistic web dashboard designed to help startups manage ongoing projects, tasks, and client tickets efficiently. The application features clean UI/UX, real-time task interaction, and structured component design.

---

## Key Features

-  **Dashboard Overview** with progress bars, task list, and ticket previews
-  **Task Management**: View, sort, and mark tasks with status tags
-  **Ticketing System**: Manage support/client inquiries with priority levels
-  **Responsive Design**: Works across desktop and tablet devices
-  **Modern UI/UX**: Clean layout with a focus on usability and clarity

---

##  Design Principles

### 1. Minimalistic & Clean Layout
- Light background with high-contrast text
- Generous use of white space for readability

### 2. Modern Font & Color Palette
- Font: Sans-serif (e.g., Inter or Roboto)
- Accent Color: **Indigo** `#4F46E5`
- Status Tags:
  -  Green: `Completed`
  -  Blue: `In Progress`
  -  Red: `Urgent` / `Overdue`

### 3. Reusable Components
- Project cards, task rows, ticket blocks with:
  - Rounded corners
  - Subtle shadows
  - Consistent layout

### 4. Interactive & Accessible
- Tooltips on icons
- Intuitive buttons with hover states
- Clear call-to-actions

### 5. Responsive Layout
- Adaptive views for desktop and tablet
- Collapsible sidebar for smooth navigation

---

##  User Flow

###  **Screen 1: Dashboard Overview**
- **Entry Point** after login
- **Top Header**: User profile, notifications, greeting
- **Projects Section**: Cards with project name, progress, team, and status
- **Task Section**: List of assigned tasks with checkboxes and deadlines
- **Tickets Section**: Recent inquiries with clickable priority badges

###  **Screen 2: Task & Ticket Detail View**
- **Tabs**: Toggle between "Tasks" and "Tickets"
- **Task View**: Sort/filter by date, status, or tags
- **Ticket View**: Ticket list with full issue details and reply options

---

##  Folder Structure (suggested)
```bash
startup-dashboard/
├── public/
├── src/
│   ├── components/
│   │   ├── ProjectCard.jsx
│   │   ├── TaskRow.jsx
│   │   └── TicketBlock.jsx
│   ├── views/
│   │   ├── Dashboard.jsx
│   │   └── TaskTicketDetail.jsx
│   └── App.js
├── package.json
└── README.md


Getting Started
1. Clone the Repository
git clone https://github.com/your-username/startup-dashboard.git
cd startup-dashboard

2. Install Dependencies
npm install
3. Run the App
npm start
License
This project is licensed under the MIT License.
