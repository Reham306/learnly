# Learnly

Learnly is an innovative web application designed to help users create, track, and manage their learning goals effectively. Whether you're an individual seeking to enhance your skills or a professional aiming to achieve career milestones, Learnly provides the tools and resources to support your journey.

With an emphasis on personalization and engagement, Learnly ensures users have access to curated educational content, personalized learning paths, and progress tracking dashboards that make achieving goals both intuitive and enjoyable.

---

## Features

### 1. **Personalized Learning Paths**
   - Build and customize your unique learning journey tailored to your goals.
   - Organize educational resources and activities in a way that works best for you.

### 2. **Curated Content**
   - Access high-quality educational resources sourced from trusted providers.
   - Discover articles, videos, and tutorials that align with your interests and objectives.

### 3. **Progress Tracking**
   - Stay motivated by monitoring your goals and achievements through interactive dashboards.
   - Visualize your learning progress and receive insights on your activities.

### 4. **Recommendations**
   - Get personalized suggestions based on your interests, completed activities, and goals.
   - Save time by finding the most relevant content with ease.

### 5. **User-Friendly Interface**
   - Navigate seamlessly with a simple and intuitive design.
   - Enjoy a distraction-free experience that keeps you focused on learning.

---

## Project Structure

### **Frontend**
- **HTML/CSS/JavaScript**: The frontend is designed to provide a clean and responsive user interface, ensuring usability across all devices.
  - Key files:
    - `learnly.html`: Main structure of the platform.
    - `register.html`: Registration page for new users.
    - `learnly.css`: Core styles for the Learnly layout.
    - `register.css`: Styling for the registration page.
    - `project.css`: Reusable styles across the platform.
    - `script.js`: Client-side functionality for interactivity.

### **Backend**
- **PHP and Node.js**: The backend ensures robust and secure functionality for user data management and server-side operations.
  - Key files:
    - `learnly.php`: Backend logic for Learnly platform.
    - `server.js`: Node.js-based server logic for enhanced backend operations.

### **Database**
- **SQL Schema**: Learnly uses a structured database to store user data and content information.
  - Key file:
    - `learnlydb.sql`: Contains the schema for managing user profiles, progress data, and curated content.

### **Images and Media**
- Visual assets are included to enhance the user experience.
  - Key files:
    - `AI.jpg`: AI-related reference image.
    - `Cover.webp` & `LEARNLY COVER.webp`: Branding and cover images for the platform.
    - `Secure User Authentication.jpg`: Diagram for secure user authentication workflow.
    - `cover 1.webp`: Alternative cover image.

### **Documentation and Logs**
- `README.md`: Comprehensive project documentation.
- `log` and `logs`: Debugging and backend activity logs.

---

## How to Run the Project Locally

### Prerequisites
1. **Install Required Software**:
   - Python (if applicable for environment setup)
   - Node.js and npm (for server operations)
   - A web server (e.g., XAMPP or WAMP for PHP files)
   - Git (for version control)

2. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

### Steps
1. **Set Up the Database**:
   - Import the `learnlydb.sql` file into your preferred database management system (e.g., MySQL).

2. **Run the Backend**:
   - For Node.js:
     ```bash
     node server.js
     ```
   - For PHP:
     - Place the PHP files in your web server's root directory (e.g., `htdocs` in XAMPP).
     - Start your server.

3. **Access the Frontend**:
   - Open `learnly.html` in your web browser or serve it using a local server.

---

## Contributing
We welcome contributions to make Learnly even better! To contribute:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes with clear and descriptive messages.
4. Push the branch and submit a pull request.

---

## Author
Reham Aly

---

## License
This project is licensed under the [MIT License](LICENSE).
