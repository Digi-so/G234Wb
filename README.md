# UI Portfolio Website

## Overview
This repository contains the source code for a personal portfolio website for **John Watson**, a UI Designer and Web Developer based in the UK. The website showcases John's skills, services, portfolio, and contact information. It is a static website built using HTML, CSS, Bootstrap, and Font Awesome for icons.

## Features
- **Responsive Design**: Fully responsive and works on all devices (desktop, tablet, mobile).
- **Sections**:
  - **Header/Hero**: Introduces John Watson with a call-to-action ("Hire Me" and "Portfolio" buttons).
  - **Bio**: Displays personal information, social media links, and contact details.
  - **Services**: Highlights services offered (Web Development, App Development, Photography).
  - **Skills**: Shows skill levels with progress bars (e.g., UI/UX Design, Ideas & Technology).
  - **Features**: Lists key strengths with icons (e.g., Web Development, Design Trends).
  - **Stats**: Displays key metrics (e.g., 135 Finished Projects, 272 Happy Customers).
  - **Portfolio**: Showcases recent work with images.
  - **Footer**
- **Styling**: Custom color scheme with dark teal (`#1A3C34`) for the header and jungle green (`#29AB87`) for buttons, icons, and the footer.

## Prerequisites
To run this project locally, you need:
- A web browser (e.g., Chrome, Firefox, Edge).
- A local server (optional but recommended for testing). Options include:
  - **VS Code Live Server** extension.
- An internet connection to load external resources (Bootstrap and Font Awesome CDNs).

## Setup Instructions
### 1. Clone the Repository
Clone this repository to your local machine:
```bash
git clone <repository-url>
cd ui-portfolio
```

### 2. File Structure
The project has the following structure:
```
ui-portfolio/
├── index.html       # Main HTML file
├── style.css        # Custom CSS file
└── README.md        # This README file
```

### 3. Run the Website
#### Option 1: Open Directly
- Double-click `index.html` to open it in your default browser.

#### Option 2: Use a Local Server
- **Using VS Code Live Server**:
  1. Open the project folder in VS Code.
  2. Right-click `index.html` and select "Open with Live Server".
- **Using http-server**:
  1. Install `http-server` if not already installed:
     ```bash
     npm install -g http-server
     ```
  2. Navigate to the project folder in your terminal.
  3. Run:
     ```bash
     http-server
     ```
  4. Open your browser and go to `http://localhost:8080`.

## Dependencies
The project uses the following external libraries:
- **Bootstrap 5.3.0**: For responsive layout and components.
  - CSS: `https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css`
  - JS: `https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js`
- **Font Awesome 6.0.0-beta3**: For icons.
  - CSS: `https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css`

