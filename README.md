
# Periskope Chat Application
Periskope is a modern real-time chat application built with Next.js, React, and Supabase. 
It offers a clean, responsive interface for messaging with contacts, searching users, and managing conversations.

## Features
- **Real-time Messaging**: Send and receive messages instantly
- **User Authentication**: Secure login and registration with Supabase Auth
- **Contact Management**: Add, search, and filter contacts
- **Message Status**: Track when messages are sent, delivered, and read
- **Responsive Design**: Works on desktop and mobile devices
- **Search Functionality**: 
  - Search existing contacts with debounced filtering
  - Add new contacts through user search
- **Message History**: View and scroll through conversation history
- **Unread Messages**: Filter to quickly find conversations with unread messages
## Deploy Link
```
https://harshaschatapp.netlify.app/auth/signin
```

## Tech Stack
- **Frontend**:
  - [Next.js 15](https://nextjs.org/) (React framework)
  - [React 19](https://react.dev/) (UI library)
  - [TailwindCSS 4](https://tailwindcss.com/) (Styling)
  - [React Icons](https://react-icons.github.io/react-icons/) (Icon components)
- **Backend**:
  - [Supabase](https://supabase.com/) (Backend-as-a-Service)
  - PostgreSQL (Database)
  - Row-Level Security (Data protection)  
- **Authentication**:
  - Supabase Auth
  - Middleware for protected routes   
    
## Getting Started

### Prerequisites

- Node.js (version 18 or newer)
- npm or yarn
- Supabase account

### Setup
**Clone the repository**

```bash
git clone https://github.com/ghv061101/Periskope_Assignment.git
cd periskope
```
**Install dependencies**

```bash
npm install
```

**Set up environment variables**

Create a `.env.local` file in the root directory with the following variables:

```
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
```
      
*Set up Supabase**

- Create a new Supabase project
- Run the SQL from `supabase-schema.sql` in the SQL editor to set up the database schema
- Set up authentication providers in the Supabase dashboard

**Run the development server**

```bash
npm run dev
```
