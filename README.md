# Christex Foundation Photography Flyer

This repository contains a simple, responsive web-based flyer for the Christex Foundation's annual photography exhibition. The flyer is designed using HTML and CSS, featuring a dark theme and a background image to enhance its visual appeal.

---

## Table of Contents
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Cloning the Repository](#cloning-the-repository)
  - [Opening in VSCode](#opening-in-vscode)
- [Usage](#usage)
  - [Running the Flyer](#running-the-flyer)
  - [Live Server Extension (Optional)](#live-server-extension-optional)
- [Customization](#customization)
  - [Editing the HTML](#editing-the-html)
  - [Editing the CSS](#editing-the-css)
  - [Changing the Background Image](#changing-the-background-image)
- [Deployment](#deployment)
  - [Deploying to GitHub Pages](#deploying-to-github-pages)
- [License](#license)

---

## Features
- Responsive design that looks great on various screen sizes.
- Dark theme with a professional look.
- Background image to enhance the visual appeal.
- Easy to customize for different events or promotions.

---

## Getting Started

### Prerequisites
Before you begin, ensure you have the following:
- A web browser (e.g., Chrome, Firefox, Safari).
- A code editor like [Visual Studio Code (VSCode)](https://code.visualstudio.com/) or any other IDE.
- Git installed (optional, for cloning the repository).

### Cloning the Repository
To get a local copy of the repository, follow these steps:
1. Open your terminal or command prompt.
2. Run the following command to clone the repository:
   ```bash
   git clone https://github.com/alfredsimeon/christex-foundation-flyer.git

### Opening in VSCode
Go to File > Open Folder and select the folder where you cloned the repository.
The project files (index.html and styles.css) will appear in the Explorer sidebar.
Usage

### Running the Flyer
Open the index.html file in your web browser:
Right-click the index.html file in VSCode’s Explorer sidebar.
Select Reveal in File Explorer (Windows) or Reveal in Finder (Mac).
Double-click the index.html file to open it in your default browser.
The flyer should now be displayed in your browser.

### Live Server Extension (Optional)
For a better development experience, you can use the Live Server extension in VSCode to automatically reload the page when you make changes:

Install the Live Server extension in VSCode.
Right-click the index.html file in VSCode and select Open with Live Server.
A new browser tab will open, and the flyer will automatically reload whenever you save changes to the HTML or CSS files.
Customization
### Editing the HTML
Open the index.html file in VSCode.
Modify the text content, headings, and links as needed. For example:
html
Run
Copy code
<h1>📸 Christex Foundation</h1>
<p>Capturing Moments, Creating Memories</p>

### Editing the CSS
Open the styles.css file in VSCode.
Change colors, fonts, and styles to match your branding or preferences. For example:
css
Run
Copy code
.header h1 {
  color: #ffcc00; /* Change the title color */
}

### Changing the Background Image
Replace the images.jpg file in the project directory with your own image.
If you use a different filename, update the CSS file:
css
Run
Copy code
body {
  background: url('your-new-image.jpg') no-repeat center center fixed;
  background-size: cover;
}

### Deployment
Deploying to GitHub Pages
To deploy the flyer to GitHub Pages:


### Push your changes to the repository:
bash
Run
Copy code
git add .
git commit -