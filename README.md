# CODTECH-task2
Name:moses
Company:CODTECH IT SOLUTION
Id:CT08DS5088
Domain:web development
mentor:neela santhosh

Overview of project

This HTML code defines a webpage for a fictional book catalog named "Booksky." Here's a summary of its structure and functionality:
Document Structure
   - The document begins with the standard `<!DOCTYPE html>` declaration and `<html>` tag.
   - The content is in English (`lang="en"`).
Head Section
   - Meta tags define the character set (`UTF-8`) and the viewport for responsive design.
   - The webpage title is set to "Booksky."
   - External styles are linked from `style.css`.
   - Fonts are imported from Google Fonts using a `link` tag with `rel="preconnect"` and `href` attributes.
Body Content
   Navbar: Contains the title "Booksky."
   Main Content
     - A container (`<div class="container">`) holds book information.
     - Each book entry (`<div class="book-container">`) includes a title (`<h2>`), author name (`<h5>`), and description (`<p>`).
     - Each book entry also features a "delete" button (`<button onclick="deletebook(event)">delete</button>`).
Popup Overlay and Box
   - Hidden by default, a popup overlay (`<div class="popup-overlay">`) and popup box (`<div class="popup-box">`) appear when adding a new book.
   - The popup box contains inputs for a book's title (`<input>`), author (`<input>`), and description (`<textarea>`).
   - Buttons inside the form allow users to add a book (`<button id="add-book">ADD</button>`) or cancel (`<button id="cancel-popup">CANCEL</button>`).
Additional Elements
    An "Add" button (`<button class="add-button" id="add-popup-button">+</button>`) triggers the display of the popup for adding a new book.
   Scripts
    External JavaScript (`<script src="script.js"></script>`) is included, suggesting additional functionality handled by client-side scripting.
This HTML structure provides a basic interface for managing and displaying books, including adding new entries and deleting existing ones using JavaScript, which would likely be defined in `script.js`.
