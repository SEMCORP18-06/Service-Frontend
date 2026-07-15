# SEMCORP Service Portal - Frontend

This repository contains the complete frontend codebase for the **SEMCORP After Sales Service Portal** client and staff management interface.

## Technology Stack
- **Framework**: Vite + React 19
- **Icons**: Lucide React
- **Styles**: Vanilla CSS Design System with light/dark theme toggle, glassmorphic UI components, and fully responsive layouts.
- **WebSockets**: Socket.io-client for real-time synchronization with the backend.

## Key Views
1. **Client Ticket Generator** (`src/views/TicketGenView.jsx`): Autocomplete company search engine with prioritized relevance scoring; allows registered and guest clients to log tickets.
2. **Client Support Portal** (`src/views/ClientDashboardView.jsx`): Real-time ticket tracker, logs timeline, and expected vs actual milestone progress graph.
3. **Staff Login** (`src/views/LoginView.jsx`): Role-based login (Service Officers, Service Managers, Field Engineers) with strict email domain checks.
4. **Service Manager Dashboard** (`src/views/ManagerDashboardView.jsx`): Workspace list, dispatch scheduler, interactive logs, and two-way WhatsApp live chat simulator.
5. **Field Engineer Panel** (`src/views/EngineerDashboardView.jsx`): Job assignments list, status updates, and service log entry tools.

## Setup & Running Locally

1. Install dependencies:
   ```bash
   npm install
   ```

2. Run the local development server:
   ```bash
   npm run dev
   ```

3. Build for production:
   ```bash
   npm run build
   ```
