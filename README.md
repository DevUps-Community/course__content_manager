# Course Content Manager Mini Project

## Objective
Build a system where admins can create and manage courses with content, and users can log in to access those courses.

## Features to Implement
1. **Admin Login:**
   - Secure admin login functionality.
2. **Course Creation:**
   - Allow admins to create and manage courses.
3. **Content Management:**
   - Enable admins to add, update, and delete course content.
4. **User Login:**
   - Allow users to register and log in to access available courses.
5. **Course Access:**
   - Allow users to view and interact with course content.

## Description
This project aims to build a course content management system where admins can create and manage courses, and users can log in to access and interact with those courses.

**Aspects to Consider:**

- **Schema Design:**
  - Plan how to store course details, content sections, user information, and user progress.
  - Consider how to efficiently link users with their accessed courses and progress.

- **React App Design:**
  - Design components for admin login, course creation, content management, user login, and course viewing.
  - Ensure state management is handled effectively, perhaps using a state management library like Redux.

- **Best Practices:**
  - Implement secure authentication and authorisation for both admins and users.
  - Ensure input validation and error handling.
  - Design a responsive and user-friendly interface.
  - Plan for scalability to add more features later, such as quizzes or certifications.

## Technical Requirements
- **Backend:** Node.js with Express
- **Database:** Supabase
- **Frontend:** React
- **Authentication:** Supabase Auth

## Steps to Build
1. **Set up the project:**
   - Initialise a new Node.js project.
   - Set up Supabase and connect it to the project.
2. **Authentication:**
   - Implement admin and user registration and login with Supabase Auth.
3. **Course API:**
   - Create endpoints to add, update, delete, and fetch courses and course content.
4. **Frontend:**
   - Build React components for:
     - Admin functionalities: login, course creation, content management.
     - User functionalities: registration, login, course viewing.
5. **Content Management:**
   - Ensure admins can structure courses into sections or modules.
   - Implement features for text content, multimedia content (videos, images), and downloadable resources.

## Future Enhancements
- Add features for quizzes or assessments within courses.
- Implement progress tracking and completion certificates.
- Allow user comments or discussions on course content.
- Integrate notifications for new content or course updates.
