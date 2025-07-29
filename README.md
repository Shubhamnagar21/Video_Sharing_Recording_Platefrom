# Video Sharing & Recording Platform

This is a full-stack web application built with Next.js that allows users to record, upload, share, and view videos. The platform features authentication, video management, user profiles, and a modern UI.

## Features

- **User Authentication**: Secure sign-in and sign-out flows.
- **Video Recording**: Record videos directly from the browser.
- **Video Upload**: Upload videos from your device.
- **Video Sharing**: Share videos with other users.
- **User Profiles**: View and manage your profile and uploaded videos.
- **Pagination**: Browse videos with paginated lists.
- **Responsive Design**: Works on desktop and mobile devices.

## Tech Stack

- **Frontend**: Next.js, React, TypeScript, CSS Modules
- **Backend**: Next.js API routes
- **Database**: Drizzle ORM
- **Authentication**: Custom auth (see `lib/auth.ts`)
- **UI Components**: Custom React components

## Getting Started

### Prerequisites

- Node.js >= 18.x
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Shubhamnagar21/Video_Sharing_Recording_Platefrom.git
   cd next_app
   ```
2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```
3. Configure environment variables:
   - Copy `.env.example` to `.env.local` and fill in required values.

4. Run database migrations:
   ```bash
   npm run migrate
   ```

5. Start the development server:
   ```bash
   npm run dev
   ```

6. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Project Structure

- `app/` - Next.js app directory (routes, layouts, pages)
- `components/` - Reusable React components
- `drizzle/` - Database config and schema
- `lib/` - Utility functions and hooks
- `public/` - Static assets (icons, images)
- `constants/` - Shared constants

## Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

## Contributing

Contributions are welcome! Please open issues or submit pull requests for improvements or bug fixes.

## License

This project is licensed under the MIT License.

## Acknowledgements

- [Next.js](https://nextjs.org/)
- [Drizzle ORM](https://orm.drizzle.team/)
- [React](https://react.dev/)
