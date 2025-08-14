# Hostel Allocation System

A modern web application for managing hostel allocations, preferences, reviews, and administration. Built with Next.js, TypeScript, and a custom in-memory database for demo purposes.

## Features

- Student and admin authentication
- Hostel and room management
- Student preferences and allocation
- Exchange requests between students
- Hostel reviews and ratings
- Responsive UI with dashboard and sidebar navigation
- Toast notifications and alerts

## Tech Stack

- [Next.js](https://nextjs.org/) (App Router, Client Components)
- [TypeScript](https://www.typescriptlang.org/)
- [React](https://react.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Radix UI](https://www.radix-ui.com/) (for accessible UI primitives)
- [Lucide Icons](https://lucide.dev/)
- Custom in-memory database (see [`lib/database.ts`](lib/database.ts))

## Project Structure

```
app/                # Next.js app directory (pages, layouts, routes)
components/         # Reusable UI and logic components
hooks/              # Custom React hooks
lib/                # Database, session, utility, and validation logic
public/             # Static assets (images, etc.)
styles/             # Additional CSS
```

## Getting Started

1. **Install dependencies:**
   ```sh
   pnpm install
   ```

2. **Run the development server:**
   ```sh
   pnpm dev
   ```
   The app will be available at [http://localhost:3000](http://localhost:3000).

3. **Build for production:**
   ```sh
   pnpm build
   ```

## Usage

- **Student Registration/Login:**  
  Register as a student and log in to set preferences, request exchanges, and review hostels.
- **Admin Panel:**  
  Admins can log in to manage hostels, rooms, and review student allocations.
- **Preferences & Reviews:**  
  Students can submit preferences and reviews for hostels.

## Customization

- **UI Components:**  
  Modify or extend components in [`components/`](components) and [`components/ui/`](components/ui).
- **Database Logic:**  
  Update or replace the in-memory logic in [`lib/database.ts`](lib/database.ts) for production use.
- **Session Management:**  
  See [`lib/session.ts`](lib/session.ts) for session logic.

## License

This project is for educational/demo purposes.  
Feel free to fork and adapt!

---

**Made with ❤️ using Next.js and
