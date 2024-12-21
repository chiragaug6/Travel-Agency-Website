# Travel Agency Webpage

## Overview

This is a simple static webpage for a travel agency, designed with HTML, CSS, and Bootstrap. It includes sections such as a hero section, about us, services, travel packages, and contact information.

---

## How to Run the Webpage Locally

Follow the steps below to run the webpage locally on your computer:

### Prerequisites

1. Ensure you have a web browser installed (e.g., Google Chrome, Mozilla Firefox, or Microsoft Edge).
2. Make sure you have a text editor or IDE like VS Code, Sublime Text, or Notepad++ for editing purposes (optional).

### Steps

1. **Download the Files**

   - Clone the repository or download the HTML, CSS, and image files into a local folder.

   ```bash
   git clone https://github.com/chiragaug6/Travel-Agency-Website.git
   ```

   Or download the ZIP file and extract its contents.

2. **Setup the Folder Structure**

   - Ensure the following folder structure:
     ```
     project-folder/
     ├── index.html
     ├── styles.css
     ```

3. **Open the HTML File**

   - Navigate to the folder containing `index.html`.
   - Right-click on `index.html` and select "Open with..." followed by your browser of choice.

4. **View the Webpage**
   - The webpage should now be displayed in your browser.

---

## Bootstrap Components Used

The following parts of the webpage utilize Bootstrap components:

### 1. **Navigation Bar**

- Implemented using Bootstrap's `navbar` component for a responsive header.

```html
<nav class="navbar navbar-expand-lg navbar-light"></nav>
```

### 2. **Hero Section**

- Utilizes Bootstrap utility classes for responsive text alignment and button styling.

```html
<div class="container h-100 d-flex flex-column justify-content-center">
  <a href="#packages" class="btn btn-primary btn-md">Explore Packages</a>
</div>
```

### 3. **Card Layout**

- Services and Travel Packages sections use Bootstrap's card component for consistent design.

```html
<div class="card mb-4 shadow-sm"></div>
```

### 4. **Grid System**

- Bootstrap's grid system is used for layout in the Services and Packages sections.

```html
<div class="row">
  <div class="col-md-4"></div>
</div>
```

### 5. **Buttons**

- Modal triggers and call-to-action buttons utilize Bootstrap's button classes.

```html
<button type="button" data-toggle="modal" class="btn btn-info"></button>
```

### 6. **Modals**

- Travel package details are displayed using Bootstrap's modal component.

```html
<div id="packageModal1" class="modal fade"></div>
```

### 7. **Form**

- The Contact Us form uses Bootstrap's form control classes for styling.

```html
<form action="#" method="#" novalidate=""></form>
```

### 8. **Footer**

- Styled using Bootstrap utility classes for spacing and text alignment.

```html
<footer class="py-4 bg-dark text-white text-center"></footer>
```

---

## External Resources

- [Bootstrap 4.5.2](https://getbootstrap.com/)
- [Font Awesome Icons](https://fontawesome.com/)

---

## Author

Developed by chirag solanki.
