Discord Clone

A simple implementation of a Discord-like interface using HTML, CSS, and TailwindCSS. This project aims to replicate the design and functionality of Discord's landing page with responsive design elements and styled components.

Features

Fully responsive layout.

TailwindCSS for styling.

Sections include:

Navigation Bar

Hero Section

Informative Sections

Footer

Technologies Used

HTML: For structure and layout.

CSS: For base styles.

TailwindCSS: For utility-based styling.

Font Awesome: For icons.

Project Structure

project-folder/
|-- images/               # Image assets used in the project
|-- style.css             # Custom CSS
|-- index.html            # Main HTML file
|-- tailwind.config.js    # Tailwind configuration

How to Run

Clone the repository:

git clone https://github.com/your-username/discord-clone.git

Navigate to the project directory:

cd discord-clone

Open the index.html file in your browser to view the project.

Tailwind Configuration

/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["*"],
  theme: {
    extend: {},
  },
  plugins: [],
  fontFamily: {
    Whitney: ["Whitney"],
    Ginto: ["Ginto"],
    ggSans: ["ggSans"],
  },
};

Preview

Below are some key sections of the webpage:

Hero Section

Features a "Download" and "Open Discord" button.

Includes a descriptive paragraph about Discord.

Informative Sections

Highlights features like "Invite-only Spaces" and "Reliable Tech".

Includes interactive buttons and visuals.

Footer

Organized into sections for "Product", "Company", "Resources", and "Policies".

Includes social media icons.

Future Enhancements

Add dynamic functionality with JavaScript.

Implement a backend for real-time interaction.

Enhance animations and transitions.

License

This project is open-source and available under the MIT License.

Feel free to contribute or suggest improvements!

