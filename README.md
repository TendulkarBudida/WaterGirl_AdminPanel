# Event Management System

This React-based Event Management System is designed to streamline the process of managing attendees, tracking attendance, and generating statistics for events. It provides an intuitive interface for administrators to handle various aspects of event management efficiently.

## Features

- **User Authentication**: Secure login system for administrators.
- **Admin Panel**: Manage user accounts and access controls.
- **File Upload**: Import attendee data from Excel files.
- **Statistics Dashboard**: View and analyze attendance data with filters and charts.
- **Real-time Attendance Tracking**: Mark attendees as present and record entry times.
- **Dynamic Reporting**: Generate and download customized reports.
- **Responsive Design**: Fully responsive interface that works on desktop and mobile devices.
- **Dark Mode**: Toggle between light an$$d dark themes for user comfort.

## Technology Stack

- **Frontend**: React.js
- **Routing**: React Router
- **UI Components**: Custom components with Radix UI primitives
- **Styling**: Tailwind CSS
- **Backend**: Supabase
- **File Handling**: XLSX library for Excel file processing
- **Icons**: Lucide React

## Getting Started

1. Clone the repository:
   ```
   git clone https://github.com/your-username/event-management-system.git
   ```

2. Install dependencies:
   ```
   cd event-management-system
   npm install
   ```

3. Set up environment variables:
   Create a `.env` file in the root directory and add your Supabase credentials:
   ```
   REACT_APP_SUPABASE_URL=your_supabase_url
   REACT_APP_SUPABASE_ANON_KEY=your_supabase_anon_key
   ```

4. Start the development server:
   ```
   npm start
   ```

5. Open [http://localhost:3000](http://localhost:3000) to view the app in your browser.

## Project Structure

- `src/components`: React components
- `src/lib`: Utility functions and Supabase client
- `src/components/ui`: Reusable UI components

<!-- # Watergirl

Watergirl is a React application designed to manage administrative tasks. This project uses React, React Router, Tailwind CSS, and Supabase for backend services.

## Project Structure
```
admin_watergirl/
    .env
    .gitignore
    package.json
    public/
        index.html
        manifest.json
        robots.txt
    README.md
    src/
        App.css
        App.js
        App.test.js
        components/
            Adminpanel.js
            CreateUser.js
            LoginPage.js
        index.css
        index.js
        reportWebVitals.js
        setupTests.js
        supabaseClient.js
    tailwind.config.js
```
## Getting Started

### Prerequisites

- Node.js
- npm or yarn

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/admin_watergirl.git
    cd admin_watergirl
    ```

2. Install dependencies:
    ```sh
    npm install
    # or
    yarn install
    ```

3. Create a [`.env`](command:_github.copilot.openSymbolFromReferences?%5B%22%22%2C%5B%7B%22uri%22%3A%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fc%3A%2FUsers%2Ftendu%2FDesktop%2FChandu%20Files%2FProgramming%2FVDC%2FWebApp%20Supabase%20API%2Fadmin_watergirl%2Fsrc%2FsupabaseClient.js%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%2C%22pos%22%3A%7B%22line%22%3A3%2C%22character%22%3A27%7D%7D%5D%2C%2287a21622-72ad-419b-84a7-78730e26081c%22%5D "Go to definition") file in the root directory and add your Supabase credentials:
    ```env
    REACT_APP_SUPABASE_URL=your-supabase-url
    REACT_APP_SUPABASE_ANON_KEY=your-supabase-anon-key
    ```

### Running the Application

To start the development server:
```sh
npm start
# or
yarn start
```

### Building the Application

To create a production build:
```sh
npm run build
# or
yarn build
```

### Running Tests

To run the tests:
```sh
npm test
# or
yarn test
```

## Project Details

### Main Components

- **App**: The main component that sets up routing.
- **LoginPage**: Component for user login.
- **AdminPanel**: Component for administrative tasks.
- **CreateUser**: Component for creating new users.

### Configuration

- **Tailwind CSS**: Configured in `tailwind.config.js`.
- **Supabase Client**: Configured in [`src/supabaseClient.js`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fc%3A%2FUsers%2Ftendu%2FDesktop%2FChandu%20Files%2FProgramming%2FVDC%2FWebApp%20Supabase%20API%2Fadmin_watergirl%2Fsrc%2FsupabaseClient.js%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%2C%2287a21622-72ad-419b-84a7-78730e26081c%22%5D "c:\Users\tendu\Desktop\Chandu Files\Programming\VDC\WebApp Supabase API\admin_watergirl\src\supabaseClient.js").

### Scripts

- **start**: Starts the development server.
- **build**: Builds the application for production.
- **test**: Runs the test suite.
- **eject**: Ejects the configuration (use with caution).

## License

This project is licensed under the MIT License.

Feel free to customize this README further to suit your project's specific needs.$$ -->