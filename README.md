# Alumni Connect

Alumni Connect is a comprehensive web-based platform designed to foster engagement and networking between educational institutions, their current students, and alumni. The platform provides dedicated, feature-rich dashboards for different user roles to streamline communication, mentorship, event management, and career development.

**Live Demo:** [https://alumni-connect017.netlify.app/](https://alumni-connect017.netlify.app/)

## 🌟 Features

The application is structured into four main portals, each tailored to a specific user role:

*   **Student Dashboard:** Connect with mentors, browse the alumni directory, access career resources, participate in forums, and view upcoming campus events.
*   **Alumni Dashboard:** Give back to the institute, offer mentorship, engage in alumni forums, and stay updated on career and networking events.
*   **Institute Dashboard:** Manage student and faculty records, oversee departments, publish announcements, maintain an institutional calendar, and track overall performance metrics.
*   **Admin Dashboard:** Oversee the entire platform, manage user profiles, review analytics, and moderate directories, forums, and announcements.

## 🛠️ Technologies Used

*   **HTML5:** Page structure and layout.
*   **CSS3:** Custom styling and responsive design.
*   **JavaScript (Vanilla):** Dynamic interactions, dashboard routing, and UI logic.

## 🚀 How to Run Locally

Since this project is built with static HTML, CSS, and JavaScript files, you do not need any complex package managers or build tools to run it on your local machine.

### Prerequisites
*   A modern web browser (Chrome, Firefox, Safari, Edge).
*   *Optional but recommended:* A code editor like [VS Code](https://code.visualstudio.com/) with the "Live Server" extension.

### Steps

1.  **Clone the repository:**
    ```bash
    git clone <your-repository-url>
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd Alumni_Connect
    ```
3.  **Run the application:**
    *   **Method 1 (Directly in Browser):** Simply double-click the `index.html` file in your file explorer, and it will open in your default web browser.
    *   **Method 2 (Using VS Code Live Server):** Open the project folder in VS Code, right-click on `index.html`, and select **"Open with Live Server"**. This will spin up a local development server and automatically reload the page when you make changes.

## 📂 Project Structure

```text
Alumni_Connect/
├── admin_dash/         # Admin-specific pages (analytics, directory, events, etc.)
├── alumni_dash/        # Alumni-specific pages (give-back, mentorship, etc.)
├── institute_dash/     # Institution-specific pages (faculty, performance, students, etc.)
├── student_dash/       # Student-specific pages (career, forum, mentor, etc.)
├── assets/             # Global CSS, JS scripts, and images (logo)
├── index.html          # Main landing page
├── login.html          # User login page
├── institution-login.html # Specific login page for institutes
└── register.html       # Account registration page
