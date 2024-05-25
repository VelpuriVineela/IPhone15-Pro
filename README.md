# iPhone 15 Pro Website Clone

This project is a clone of the iPhone 15 Pro website, created using React and other modern web technologies. It includes various components, assets, utilities, animations, and 3D models to replicate the official website's look and feel.

## Table of Contents

- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Components](#components)
- [Assets](#assets)
- [Animations](#animations)
- [3D Models](#3d-models)
- [Utils](#utils)
- [Constants](#constants)
- [Acknowledgements](#acknowledgements)
- [Hosted Link](#hosting-link)


## Project Structure

The project is organized as follows:

```bash
   APPLE_WEBSITE/
├── node_modules/
├── public/
│ └── assets/
│ ├── images/
│ │ ├── apple.svg
│ │ ├── bag.svg
│ │ ├── black.jpg
│ │ ├── blue.jpg
│ │ ├── chip.jpeg
│ │ ├── explore1.jpg
│ │ ├── explore2.jpg
│ │ ├── frame.png
│ │ ├── hero.jpeg
│ │ ├── pause.svg
│ │ ├── play.svg
│ │ ├── replay.svg
│ │ ├── right.svg
│ │ ├── search.svg
│ │ ├── watch.svg
│ │ ├── white.jpg
│ │ └── yellow.jpg
│ ├── videos/
│ │ ├── explore.mp4
│ │ ├── frame.mp4
│ │ ├── hero.mp4
│ │ ├── highlight-first.mp4
│ │ ├── highlight-fourth.mp4
│ │ ├── highlight-sec.mp4
│ │ ├── highlight-third.mp4
│ │ └── smallHero.mp4
│ ├── react.svg
│ └── vite.svg
├── src/
│ ├── components/
│ │ ├── Features.jsx
│ │ ├── Footer.jsx
│ │ ├── Hero.jsx
│ │ ├── Highlights.jsx
│ │ ├── HowItWorks.jsx
│ │ ├── IPhone.jsx
│ │ ├── Lights.jsx
│ │ ├── Loader.jsx
│ │ ├── Model.jsx
│ │ ├── ModelView.jsx
│ │ ├── Navbar.jsx
│ │ └── VideoCarousel.jsx
│ ├── constants/
│ │ └── index.js
│ ├── utils/
│ │ ├── animations.js
│ │ └── index.js
│ ├── App.jsx
│ ├── index.css
│ └── main.jsx
├── .gitignore
├── package.json
└── README.md
```


## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:

   ```bash
    cd APPLE_WEBSITE
   ```

3. Install the dependencies:

  ```bash
    npm install
  ```

## Usage

To run the project locally, use the following command:

```bash
  npm start
```

This will start the development server, and you can view the website in your browser at `http://localhost:3000`.


## Features

- **Responsive Design**: The website is fully responsive and works on various devices and screen sizes.
- **Interactive Animations**: Smooth and interactive animations enhance the user experience.
- **3D Models**: Detailed 3D models of the iPhone 15 Pro, viewable and interactable directly on the website.
- **Video Integration**: High-quality videos showcasing the iPhone 15 Pro features and highlights.
- **Modular Components**: Clean and modular React components for easy maintenance and scalability.

## Components

- **Features.jsx**: Contains the features section of the website.
- **Footer.jsx**: Contains the footer of the website.
- **Hero.jsx**: Contains the hero section of the website.
- **Highlights.jsx**: Contains the highlights section of the website.
- **HowItWorks.jsx**: Contains the "How It Works" section of the website.
- **IPhone.jsx**: Contains the main iPhone 15 Pro details section.
- **Lights.jsx**: Contains the lighting effects used in the website.
- **Loader.jsx**: Contains the loading screen component.
- **Model.jsx**: Contains the 3D model viewer for the iPhone.
- **ModelView.jsx**: Contains the main view for displaying the 3D model.
- **Navbar.jsx**: Contains the navigation bar of the website.
- **VideoCarousel.jsx**: Contains the video carousel component.

## Assets

- **Images**: Various images used in the website, stored in `public/assets/images`.
- **Videos**: Various videos used in the website, stored in `public/assets/videos`.
- **Models**: 3D models used in the website, stored in `public/assets/models`.

## Animations

The project utilizes advanced CSS and JavaScript animations to create a smooth and interactive user experience. Animations are handled in `src/utils/animations.js`, where you can find utility functions that define how elements transition and behave on user interactions.

## 3D Models

The 3D models of the iPhone 15 Pro are an integral part of this project. These models are stored in `public/assets/models/` and are rendered using the `Model.jsx` and `ModelView.jsx` components. These models provide an interactive experience, allowing users to view and explore the iPhone 15 Pro from different angles.

## Utils

- **animations.js**: Contains utility functions for animations.
- **index.js**: Contains general utility functions.

## Constants

- **index.js**: Contains constant values used throughout the project.



## Acknowledgements

- Inspired by the official Apple iPhone 15 Pro website.
- Built with React and other modern web technologies.


## Hosted Link

- https://iphone15-pro-clone.netlify.app/
