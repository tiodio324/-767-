# Data Vault - Your Personal Digital Storage

DataVault is a responsive web application for storing and accessing your files, links, and notes across multiple devices. Built with React and Firebase Realtime Database, it provides a seamless experience whether you're on a smartphone or computer.

## Features

- **Responsive Design**: Fully adaptive interface that works well on any device
- **File Storage**: Upload, download, and manage files 
- **Link Management**: Save and organize important URLs
- **Note Taking**: Store quick notes and important information
- **Dark Mode**: Toggle between light and dark themes for comfortable viewing in any environment
- **Persistent UI State**: Your selected tab and theme preference are saved between sessions
- **Real-time Database**: All data is stored in Firebase Realtime Database for instant access across devices

## Getting Started

1. Clone the repository
2. Install dependencies with `npm install`
3. Create a `.env` file with your Firebase configuration:
   ```
   VITE_BACKEND_URL = 'your-firebase-url'
   ```
4. Run the development server with `npm run dev`
5. Build for production with `npm run build`

## Technologies Used

- React 19
- Firebase Realtime Database
- Vite
- SCSS for styling
- Responsive design with Flexbox and CSS Grid

## Usage

- **Files Tab**: Upload files by dragging and dropping or using the file picker. Download or delete files as needed.
- **Links Tab**: Add links with titles and descriptions. Click to visit or delete links.
- **Notes Tab**: Create, view, and manage your notes.

## Implementation Details

- Files are stored as base64-encoded strings in the Realtime Database
- Dark mode and active tab preferences are saved in localStorage
- All data is stored using the Firebase Realtime Database (no Firebase Storage required)

## License

MIT
