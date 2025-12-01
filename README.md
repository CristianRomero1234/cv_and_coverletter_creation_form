# CV and Cover Letter Generator

## Version
- 1.0 (Dec,1 2025)

## Purpose

This project is a simple, self-contained tool to quickly generate a professional-looking CV (Curriculum Vitae) and a Cover Letter. It is designed for users who need to create and customize these documents easily without any complex setup. The tool is a single HTML file that runs entirely in your web browser.

## How to Use

1.  **Open `index.html`:** Simply open the `index.html` file in your preferred web browser (e.g., Chrome, Firefox, Safari).
2.  **Fill in the Form:** A web form will be displayed. Fill in your personal information, work experience, education, and other details.
3.  **Customize Sections:** You can dynamically add or remove sections like "Work Experience," "Education," and "Skills" by using the "Add" and "Remove" buttons associated with each section.
4.  **Download as PDF:** Once you have filled in all the necessary information, click the "Download CV and Cover Letter as PDF" button at the bottom of the page. This will generate and download two separate PDF files: one for your CV and one for your Cover Letter.

## Features

*   **No Server Needed:** This is a purely client-side application that runs entirely in your browser. No internet connection is required after the initial page load (as the necessary libraries are loaded from a CDN).
*   **Dynamic Form:** Easily add or remove entries for your work experience, education, skills, and languages to fit your needs.
*   **PDF Export:** Generates clean, professional-looking PDF documents directly from the browser.
*   **Easy to Modify:** The entire tool is contained within a single `index.html` file. The HTML, CSS, and JavaScript can be easily modified by anyone with basic web development knowledge.

## Technologies Used

*   **HTML:** For the structure of the web form and the document templates.
*   **CSS:** For styling the form and the documents.
*   **JavaScript:** To handle the form logic, dynamic sections, and template processing.
*   **jsPDF:** A library to generate PDF files in the browser.
*   **html2canvas:** A library to render the HTML templates as images, which are then used by jsPDF to create the PDF.
