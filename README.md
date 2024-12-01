# Layerpath Analytics

## Overview
Layerpath Analytics is a user-friendly platform designed to manage workspace activities, track progress, and analyze appointment details with an intuitive UI. The layout is divided into two main sections: a static **Sidebar** for navigation and a **Main Content Area** for displaying data and analytics.

---

## Screenshots

### Screen 1: Dashboard Overview
![Screen 1](https://github.com/user-attachments/assets/d04ae1bd-e531-414e-964c-cf23e9f52314)

---

### Screen 2: Sidebar with Navigation Items
![Screen 2](https://github.com/user-attachments/assets/98db2801-80f9-4b00-9bd7-49a76f1c71cd)

---

### Screen 3: Checklist Progress and contact CTA section
![Screen 3](https://github.com/user-attachments/assets/23bcbe24-d64d-42af-8eb4-0e3d3f1391f1)

---

### Screen 4: Contact and Appoinment Details and bar Analysis
![Screen 4](https://github.com/user-attachments/assets/4f0deba1-39b1-4430-857c-cb6d62b87e58)

---

### Screen 5: Profile and User Info with full overview of Analytics
![Screen 5](https://github.com/user-attachments/assets/b6ce0f8d-6638-4b1b296f3e80)

---

## Layout Structure

### 1. **Sidebar (Aside Section)**
- The sidebar is static for large screens and scrollable for overflow content.
- On small screens:
  - The sidebar remains hidden initially.
  - Clicking the sidebar toggle button makes it visible.
- Contains:
  - Logo
  - Navigation menu items
  - Checklist for user tasks
  - Contact section with demo button
  - User profile information at the bottom

---

### 2. **Main Content Area**
- Includes:
  - A header with navigation items.
  - Detailed views of appointments and analytics data with toogle button for show analytics through modal
  - A modal popup screen for:
    - Contact information.
    - Analytics summary for specific users or activities.

---

## Features
1. **Responsive Sidebar**:
   - Visible by default on larger screens.
   - Toggles visibility on smaller screens for seamless navigation.

2. **Main Content**:
   - Displays critical workspace information.
   - Organized into sections for:
     - Appointments
     - Analytics
     - Descriptive summaries.

3. **Modal Popups**:
   - Show user contact details.
   - Provide analytics insights.

4. **Checklist**:
   - Tracks user progress through tasks with a dynamic progress bar.

5. **User Profile**:
   - Displays profile image, name, and email for personalized experience.

---

## File Structure

```plaintext
layerpath-analytics/
├── images/                 
├── index.html
├── index.css   
└── README.md              
