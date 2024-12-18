# WhatZA

![React](https://img.shields.io/badge/React-18.2.0-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

WhatZA is a clone of the WhatsApp Web login page and Chat feature, created using React and styled to closely resemble the original design. This project showcases web development practices, UI/UX design, and the use of modern front-end libraries to match a real-world app interface.

## Table of Contents

- [Project Overview](#project-overview)
- [Demo](#demo)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [File Structure](#file-structure)
- [Backlog](#backlog)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The **WhatsApp Web Clone** replicates the login page of WhatsApp Web, including the layout, colors, and styling details. It is built with **React** and custom **CSS** and focuses on accurate UI/UX design to provide a realistic experience.

## Demo

![Screenshot of WhatsApp Web Clone](https://github.com/AmirHaytham/whatsapp-login-page/blob/main/screenshots/Login.png)

You can also view a live demo here: [Live Demo Link](https://your-demo-link.com)

## Features

- 📱 **Responsive Design**: Adapts to various screen sizes for mobile, tablet, and desktop.
- 📸 **QR Code Integration**: Generates a placeholder QR code for demonstration purposes.
- ⬇️ **Download Button**: Styled "Download" button with an icon for better UX.
- 🎨 **Accurate UI Clone**: Designed to mimic the look and feel of the WhatsApp Web login page.

## Installation

To set up this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/whatsapp-web-clone.git
   cd whatsapp-web-clone
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Run the development server**:
   ```bash
   npm start
   ```

4. Open `http://localhost:3000` in your browser to view the project.

## Usage

Once the project is running, you can explore the following functionalities:

- View the WhatsApp Web login interface clone.
- Check the responsive design by resizing your browser window.

## Technologies Used

- **React**: For building UI components and managing state.
- **CSS**: Custom styling to replicate the original WhatsApp design.
- **QRCode.react**: For generating and displaying a QR code as a placeholder.

## File Structure

```
whatsapp-web-clone/
├── public/
│   ├── index.html
│   └── whatsapp-logo.svg  # WhatsApp logo used in the project
├── src/
│   ├── App.js             # Main application component
│   ├── WhatsAppLoginPage.js # Login page component
│   ├── App.css            # Global styling
│   └── index.js           # Entry point for React
├── .gitignore
├── package.json
└── README.md
```
## Backlog

The following are potential future improvements and features for this project:

- [x] **Enhanced QR Code Functionality**: Integrate a real WhatsApp QR code for actual login functionality.
- [x] **Chat Interface After Login**: Create a chat interface that appears after logging in with the QR code, allowing users to view and send messages.
- [ ] **Multilingual Support**: Add language options to support a wider audience.
- [ ] **Dark Mode**: Implement a dark mode toggle to improve accessibility and user preference.
- [ ] **Unit and Integration Testing**: Add tests using Jest and React Testing Library to ensure reliability and maintainability.
- [x] **Animations**: Add subtle animations for QR code generation and button interactions to enhance UX.
- [ ] **Accessibility Improvements**: Improve keyboard navigation and ARIA attributes to make the app more accessible.
- [x] **Error Handling**: Add error handling for invalid QR codes or loading failures.
- [ ] **Deployment**: Deploy the app on GitHub Pages, Vercel, or Netlify for easier access and sharing.

Feel free to suggest additional features or improvements by opening an issue or contributing directly!

## Contributing

We welcome contributions! If you'd like to contribute, follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Push to your branch (`git push origin feature-branch`).
5. Open a Pull Request.

For major changes, please open an issue first to discuss your ideas.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

Made with ❤️ by [Amir](https://github.com/AmirHaytham)
