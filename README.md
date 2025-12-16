# European Learning Institute - Platform Documentation

## Project Overview
This project is a modern, responsive educational platform designed for the **European Learning Institute**. It consists of three main modules:

1.  **Public Website**: Landing page, course listing, about, and contact sections.
2.  **Student Portal**: Secure login, signup, dashboard, and document management.
3.  **Admin Panel**: Management interface for students, courses, and announcements.

## Technology Stack
-   **Frontend**: HTML5, CSS3 (Modern Variables), Bootstrap 5.3 Framework.
-   **Aesthetics**: Glassmorphism, Soft Gradients, Inter Typography (2025 Standard).
-   **Backend Ready**: Firebase Configuration file included in `assets/js/firebase-config.js`.

## Folder Structure
```
/public             # Public facing files
  /assets           # Shared resources
    /css            # main.css (Core styles)
    /js             # Utility scripts
    /images         # Project images
  index.html        # Landing Page
  courses.html      # Course Listing
  about.html        # Institute Info
  contact.html      # Inquiry Form

/student            # Student Portal
  login.html        # Student Auth
  signup.html       # Student Registration
  dashboard.html    # Main Student Hub
  form.html         # Printable Registration Form
  idcard.html       # Printable ID Card

/admin              # Admin Panel
  index.html        # Admin Login
  dashboard.html    # Analytics Overview
  students.html     # Student Management
  courses.html      # Course Management
```

## How to Run
Since this is a client-side implemented project (static files), you can run it by:
1.  **Opening `public/index.html`** in any modern browser.
2.  Using a local server like Live Server (VS Code Extension) for the best experience.

## Next Steps
-   **Firebase Integration**: Connect the `firebase-config.js` with your actual Firebase Console project keys.
-   **Dynamic Logic**: Replace the mock data in HTML files with real-time Firestore data fetching using the provided JS hooks.
"# EUROPEAN-LEARNING-INSTITUTE" 
