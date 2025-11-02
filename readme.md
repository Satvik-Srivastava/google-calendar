# Google Calendar Clone

A feature-rich calendar application inspired by Google Calendar, built from scratch without using any calendar library. The application helps in creating meetings, managing day-to-day activities, and organizing events efficiently.

## Features Implemented

- 📅 Custom calendar implementation using dayjs
- ✨ Create, edit, and delete events
- 👥 Invite registered users to events
- 🗓️ Month and day view options
- 🎨 Event color coding and status management
- 🔍 Filter events by type and status
- 👤 User authentication system
- 📱 Responsive design
- 📝 Rich text editor for event descriptions
- 🎯 Event status tracking

## Technology Stack

### Frontend
- **React 18** - UI library with Context API for state management
- **Vite** - Build tool and development server
- **TailwindCSS** - Utility-first CSS framework
- **DayJS** - Lightweight date manipulation
- **React Quill** - Rich text editor for event descriptions
- **React Hook Form** - Form validation and handling
- **Yup** - Schema validation
- **Axios** - HTTP client
- **React Router DOM** - Client-side routing

### Backend
- **Node.js** - Runtime environment
- **Express** - Web framework
- **MongoDB** - Database
- **Mongoose** - MongoDB ODM
- **JWT** - Authentication
- **Cloudinary** - Image upload and hosting
- **Formidable** - Form data parsing
- **Cors** - Cross-origin resource sharing

## Setup Instructions

### Prerequisites
- Node.js (v14 or higher)
- MongoDB installed and running
- Git

### Frontend Setup
1. Clone the repository and install dependencies:
   ```bash
   git clone [repository-url]
   cd google-calendar-clone
   npm install
   ```

2. Create a `.env` file in the root directory:
   ```env
   VITE_API_URL=http://localhost:4000
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

### Backend Setup
1. Navigate to the api directory and install dependencies:
   ```bash
   cd api
   npm install
   ```

2. Create a `.env` file in the api directory:
   ```env
   MONGODB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret_key
   PORT=4000
   CLOUDINARY_NAME=your_cloudinary_name
   CLOUDINARY_API_KEY=your_cloudinary_api_key
   CLOUDINARY_API_SECRET=your_cloudinary_api_secret
   ```

3. Start the backend server:
   ```bash
   npm start
   ```

The application will be running at `http://localhost:5173` with the API at `http://localhost:4000`.

## Future Enhancements

1. **Calendar Views**
   - Week view implementation
   - Year view
   - Agenda view
   - Mini calendar widget

2. **Event Features**
   - Recurring events
   - Event reminders and notifications
   - Event attachments
   - Custom event categories

3. **User Experience**
   - Drag and drop event management
   - Multiple calendar support
   - Calendar sharing
   - Dark mode support

4. **Technical Improvements**
   - Real-time updates using WebSocket
   - Offline support with service workers
   - Unit and integration tests
   - Mobile app version



## Previews

#### Month view
![image](public/googlecalendarclone.png)

#### Day view
![image](public/2023-05-22_225209.png)

### Add Event Modal
![image](public/2023-05-22_232200.png)