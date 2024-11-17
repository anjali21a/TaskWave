## TaskWave

## Description
This is a real-time Todo application built using React and Firebase. The application allows users to manage their tasks efficiently by adding, editing, and deleting items. With the integration of Firebase, any changes made are updated and reflected in real-time across all connected clients.

## Features
- **Add Tasks**: Users can create new tasks with ease.
- **Edit Tasks**: Update task details directly within the app.
- **Delete Tasks**: Remove completed or unwanted tasks.
- **Real-Time Updates**: Changes are immediately reflected for all users connected to the application.
- **Persistent Data**: Tasks are stored in Firebase, ensuring data is not lost on page reload.
- **User Authentication (Optional)**: Secure user-specific task management.

## Technologies Used
- **React**: Front-end library for building the user interface.
- **Firebase**: Backend-as-a-Service for real-time database and hosting.
- **JavaScript (ES6)**: Scripting language for app logic.
- **CSS**: Styling for a clean and responsive design.

## Setup and Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/anjali21a/taskwave.git
   ```
2. Navigate to the project directory:
   ```bash
   cd realtime-todo-app
   ```
3. Install the dependencies:
   ```bash
   npm install
   ```
4. Create a Firebase project and add your configuration to the project.
   - Copy the Firebase configuration object from your Firebase console.
   - Create a `.env` file in the project root and add your Firebase credentials:
     ```bash
     REACT_APP_FIREBASE_API_KEY=your-api-key
     REACT_APP_FIREBASE_AUTH_DOMAIN=your-auth-domain
     REACT_APP_FIREBASE_PROJECT_ID=your-project-id
     REACT_APP_FIREBASE_STORAGE_BUCKET=your-storage-bucket
     REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your-messaging-sender-id
     REACT_APP_FIREBASE_APP_ID=your-app-id
     ```
5. Start the development server:
   ```bash
   npm start
   ```
6. Open the app in your web browser at `http://localhost:3000`.

## Usage
1. **Add Task**: Enter a task in the input field and click the "Add" button.
2. **Edit Task**: Click on a task to modify its content and save the changes.
3. **Delete Task**: Click the delete icon next to the task to remove it.
4. **View Real-Time Updates**: Open the app on multiple devices or browsers to see changes reflected instantly.

## Future Enhancements
- **User Authentication**: Add user sign-in to enable task management per user.
- **Task Categorization**: Allow users to categorize tasks (e.g., Work, Personal).
- **Due Dates and Reminders**: Add options for setting task due dates and notifications.
- **Dark Mode**: Implement a dark theme for improved user experience.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your improvements.


## Contact
For any questions or feedback, please contact connectkumarianjali@gmail.com.

