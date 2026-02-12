# Odoo Design Exercise

Created by: Andrés Orihuela Otero


## Tech Stack

- **HTML5:** Semantic markup structure.
- **CSS3 (Sass):** Styling with SCSS for maintainability.
- **Bootstrap 5.3:** Responsive layout and component framework (v5.3).
- **Lucide Icons:** Modern and consistent iconography.

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

- [Node.js](https://nodejs.org/) installed on your machine.
- `npm` (usually comes with Node.js).

### Installation

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/AndresOrh/Odoo-Design-Exercise.git
    cd odoo-design-excercise
    ```

2.  **Install dependencies:**

    ```bash
    npm install
    ```

3.  **Compile Sass:**
    To watch for changes and automatically compile Sass to CSS during development:

    ```bash
    npm run sass
    ```

    To perform a one-time build:

    ```bash
    npm run build
    ```

4.  **Open the project:**
    Open `index.html` in your preferred web browser to view the site.

## File Structure

```
odoo-design-excercise/
├── assets/
│   ├── css/          # Compiled CSS files
│   ├── img/          # Images and icons
│   ├── scss/         # Sass source files
│   └── js/           # Custom JavaScript files (not used in this excercise)
├── node_modules/     # Project dependencies
├── index.html        # Main HTML file
├── package.json      # NPM scripts and dependencies
└── README.md         # Project documentation
```

## VS Code Extensions used in this exercise
- Prettier (For code formatting)

## Comments and main changes
- The layout for mobile devices is a simple responsive layout that adjuste everything into a single column for every section.
- Some icons were changed for consistency with daily use apps.
