# Full-Stack-Job-Portal
 Full Stack Job Portal with React JS, Tailwind CSS, Supabase, Clerk, Shadcn UI Tutorial 🔥🔥
A Full Stack Job Portal built with React JS, Tailwind CSS, Supabase, Clerk, and Shadcn UI combines modern web technologies to create a powerful and visually appealing platform for job seekers and recruiters. This type of project is ideal for showcasing full stack skills on GitHub, as it demonstrates expertise in frontend, backend, authentication, and UI component libraries.​​

Project Overview
This job portal offers secure authentication, job postings, application tracking, and responsive user experiences. Clerk handles user authentication, ensuring secure access and management for both companies and job seekers, while Supabase serves as the backend for data storage, job listing management, and real-time updates. Shadcn UI and Tailwind CSS provide a clean, modern, and responsive design system for building polished user interfaces.​​

Core Features
User Authentication: Secure login and registration using Clerk, integrated with Supabase.​

Job Listings & Search: Users can browse jobs, filter by criteria, and view detailed postings.​

Job Post Management: Recruiters/companies can post, edit, and delete job openings via protected routes.​​

Application Tracking: Job seekers can apply to jobs, track their applications, and save opportunities for later.​

Role-Based Access: Distinct dashboards and permissions for recruiters (job posting, managing applicants) and candidates (applying, viewing applications).​

Modern UI Components: Shadcn UI supplies reusable components such as modals, accordions, carousels, and forms, styled with Tailwind CSS for responsiveness and theme support (including dark mode).​​

Form Validation: React Hook Form and Zod validation ensure smooth, error-free user input experiences.​​

Tech Stack
Purpose	Technology	Details
Frontend	React JS	SPA architecture, state management with Context API​​
Styling/UI	Tailwind CSS	Utility-first, mobile-friendly styling​​
UI Components	Shadcn UI	Customizable, accessible UI library​​
Backend/Database	Supabase	Auth, Postgres DB, real-time data​​
User Authentication	Clerk	SSO, OAuth, session management​​
Form Handling	React Hook Form, Zod	Seamless form validation​​
Typical Folder Structure

The typical structure includes:

/src/components: Reusable UI components built with Shadcn UI.​​

/src/pages: Route-based pages (Home, Jobs, Profile, Onboarding, etc.).​​

/src/hooks: Custom React hooks for Supabase and Clerk integration.​​


### Make sure to create a `.env` file with following variables -

VITE_SUPABASE_URL=
VITE_SUPABASE_ANON_KEY=
VITE_CLERK_PUBLISHABLE_KEY=


/src/styles: Tailwind CSS configuration and global styles.​

/src/lib: Utility functions (e.g., for Supabase queries).​

