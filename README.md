### **Enhanced To-Do Application**

Welcome to the **Enhanced To-Do Application**! This project is a modern and responsive task management tool that combines basic to-do list functionality with real-time weather updates and user authentication. Built with React, Redux, and Redux Thunk, it is designed to showcase state-of-the-art front-end development practices while being simple and intuitive for users.

---

## **Features**

###  **Core To-Do Functionality**
- **Add Tasks**: Quickly add tasks along with their priority levels (High, Medium, Low).
- **View Tasks**: Display all tasks in a structured, easy-to-read list format.
- **Delete Tasks**: Remove tasks you’ve completed or no longer need.
- **Task Prioritization**: Sort tasks by priority to focus on what matters most.

###  **Weather Integration**
- Fetches real-time weather updates for tasks associated with outdoor activities or specific locations.
- Provides helpful details such as temperature, condition, and humidity.

###  **User Authentication**
- Mock login and logout functionality to simulate a secure and personalized experience.
- Ensures task visibility only for logged-in users.

### **Persistent Storage**
- Saves tasks and user authentication state in `localStorage` for data persistence across sessions.

###  **Responsive Design**
- Fully optimized for mobile, tablet, and desktop devices.
- Designed using CSS Grid and Flexbox for a seamless, mobile-first user experience.

---

## **Technology Stack**

### **Frontend**
- **React**: Component-based user interface.
- **Redux Toolkit**: Advanced state management.
- **Redux Thunk**: Middleware for handling asynchronous actions.
- **Axios**: For making API requests.

### **Styling**
- **CSS**: Custom and responsive styling.
- **Bootstrap or Material-UI** (optional): For pre-styled components.

### **API**
- **OpenWeatherMap**: For fetching real-time weather data.

---

## **Setup Instructions**

### **1. Prerequisites**
- Node.js and npm installed on your system.
- An API key from [OpenWeatherMap](https://openweathermap.org/api).

### **2. Installation**
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/enhanced-todo-app.git
   cd enhanced-todo-app
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up environment variables:
   - Create a `.env` file in the root directory.
   - Add your OpenWeatherMap API key:
     ```env
     REACT_APP_WEATHER_API_KEY=your_api_key_here
     ```

### **3. Run the Application**
Start the development server:
```bash
npm start
```

---

## **Project Structure**

Here's a quick overview of the project's structure:

```
/src
├── /components        # React components (TaskInput, TaskList, WeatherInfo)
├── /features          # Redux slices for auth and tasks
├── /store             # Redux store configuration
├── /utils             # Utility files (e.g., API calls)
├── /styles            # CSS files
├── App.js             # Root component
├── index.js           # Application entry point
└── index.css          # Global styles
```

---

## **How It Works**

### **Add a Task**
1. Enter a task in the input field.
2. Select a priority level (High, Medium, or Low).
3. Click the "Add Task" button or press Enter.

### **View and Delete Tasks**
- All tasks are listed below the input field with their priority levels.
- Each task has a delete button to remove it from the list.

### **Weather Integration**
- If a task has weather data available, the weather is displayed below the task.
- The weather includes the temperature, condition, and humidity.

### **Login/Logout**
- Use the "Login" button to authenticate.
- Once logged in, you can access and manage your tasks.
- Use the "Logout" button to simulate signing out.

---

## **Responsive Design**

The application is built with a mobile-first approach:
- On mobile, components stack vertically for easy navigation.
- On larger screens, components align horizontally for efficient use of space.

---

## **Contributing**

We welcome contributions! If you’d like to contribute:
1. Fork the repository.
2. Create a new branch for your feature:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature-name"
   ```
4. Push your branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

---

## **License**

This project is licensed under the **MIT License**. See the `LICENSE` file for more details.

---

## **Acknowledgments**

- [OpenWeatherMap](https://openweathermap.org/) for the weather API.
- The React and Redux communities for their excellent tools and documentation.

---
