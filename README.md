# GovWait – Frontend (Public Wait Time Analytics)

## Project Description

GovWait is a frontend application developed to provide improved visibility into waiting times in public service offices. The objective of this system is to enhance transparency and improve the experience of citizens interacting with government services.

The application enables users to view estimated wait times, understand crowd conditions, and access basic analytical insights. The design emphasizes simplicity, usability, and scalability, allowing easy integration with backend systems in future.

---

## Features

- View nearby offices along with current wait times  
- Display estimated waiting duration and crowd status  
- Provide a simple user check-in interface  
- Offer a basic dashboard for administrative insights  
- Follow a modular and scalable frontend architecture  

---

## Tech Stack

The following technologies are used in the development of this frontend:

- Next.js (App Router)  
- TypeScript  
- Tailwind CSS with shadcn UI  
- Zustand for state management  
- React Hook Form for form handling  
- Zod for validation  
- Axios for API communication  

---

## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/vikaskumar2500/frontend_waittime.git
cd frontend_waittime
```

---

### 2. Install Dependencies

```bash
pnpm install
```

---

### 3. Run the Application

```bash
pnpm dev
```

Open the application in your browser:

```
http://localhost:3000
```

---

## Project Structure

The project follows a feature-based structure to maintain clarity and scalability:

```
src/
├── app/                # Application routing (Next.js App Router)
├── components/         # Reusable UI components
├── features/           # Feature-specific modules (auth, wait-time, etc.)
├── store/              # Global state management (Zustand)
├── lib/                # Utility functions and API client
├── hooks/              # Custom reusable hooks
├── mock/               # Mock data for development
├── types/              # TypeScript type definitions
```

---

## Dependencies

All required dependencies are listed in the `package.json` file.

To install them, run:

```bash
pnpm install
```

---

## Notes

- This project is a frontend-only implementation  
- Backend APIs can be integrated later without major structural changes  
- Mock data is used during development  
- The architecture is designed for scalability and maintainability  

---