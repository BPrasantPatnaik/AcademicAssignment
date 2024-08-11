# 7th Semester IT Courses Website

## Overview

The **7th Semester IT Courses Website** is an interactive online platform designed to present a comprehensive catalog of IT courses available in the 7th semester of an academic program. This website allows students, educators, and prospective learners to easily access essential information regarding the courses offered, including details such as course titles, credits, instructors, and specific course objectives.

### Key Features

- **Course Listings**: Organized courses categorized into theory and lab sections.
- **Responsive Design**: Designed to work well on both desktop and mobile devices.
- **Detailed Course Information**: Each course page includes various details such as:
  - Course Title
  - Number of Credits
  - Theory/Lab Classification
  - Class Timings
  - Classroom Numbers
  - Instructor's Name (with a link to their personal website)
  - Instructor's Photo
  - Course Objectives and Outcomes
  - Modules covered
  - Assignment status and links to materials provided by the instructor
  - Extra readings and quiz questions.

## Prerequisites

Before you start using the website, ensure that you have the following:

- A modern web browser (e.g., Google Chrome, Mozilla Firefox, Safari).
- Basic understanding of HTML/CSS if you wish to modify or extend the website.
- No server configuration is required since the site can be run locally.

## Setup Instructions

Follow these instructions to set up and run the website locally:

1. **Download or Clone the Repository**:
   - You can download the files as a ZIP archive or clone the repository using:
     ```bash
     git clone <repository-url>
     ```

2. **File Structure**:
   Ensure that your directory structure looks something like this:
/path/to/your/project/
 ├── index.html
 ├── course1.html
 ├── course2.html
 ├── course3.html
 ├── course4.html
 ├── course5.html
 ├── course6.html
 ├── course7.html
 ├── css/ │
     └── styles.css
 ├── js/ │
    └── scripts.js
 └── images/ (place instructor images here)


3. **Run the Website**:
- Open the `index.html` file directly in your web browser. If you are familiar with local servers, you may also use a simple HTTP server. For example, using Python:
  ```bash
  python -m http.server
  ```
- Then navigate to `http://localhost:8000` in your web browser.

4. **Accessing Course Pages**:
- Click on any course title from the homepage to navigate to the course details page, where you'll find all relevant course information laid out clearly.

## Using the Website

Once you have the website up and running, you can:

- **Browse the Courses**: The homepage features a list of all available courses.
- **View Course Details**: Click on any course link to view:
- Instructor photo and name
- Course objectives and outcomes
- Detailed modules covered during the course
- Assignment status and links to course materials
- Quiz questions for self-assessment.

### Example Course Pages

Each course page contains the following sections:

1. **Course Title**: The name of the course.
2. **Number of Credits**: Total credits assigned to the course.
3. **Theory/Lab**: Indicates if the course is a theory or lab.
4. **Class Time and Classroom**: Actual timings and locations (to be updated).
5. **Instructor Information**: 
- Instructor Name linking to their personal website.
- Instructor Photo.
6. **Course Objectives**: Goals of what the course intends to achieve.
7. **Course Outcomes**: Expected skills or knowledge students will gain.
8. **Modules**: Topics divided into different modules indicating course coverage.
9. **Assignments**: Status and links to the assignments assigned during the course.
10. **Downloadable Materials**: Links to course materials provided by the instructor.
11. **Extra Readings**: Suggested readings for deeper understanding.
12. **Quiz Questions**: Sample questions to assess your understanding of the topics.

## Contribution

Contributions are welcome! If you have suggestions or improvements, please submit an issue or open a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.


