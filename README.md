# Rest Countries Api

An app for travelers to track all the cities they have been to on a map.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)

---

## Overview

Users can register all the cities they have ever traveled to and write a short note about them. Grouped in cities and countries.
This project focuses on how to work with map with react.

## Features

- Click on any city on the map to add it to the list.
- Click on the 'use position' button to take the map to your current position, then select a city:
  This is a location-based feature that utilizes geolocation to enhance user experience.
- On the list of cities, click on a particular city to open more details about the trip and take the map to that particular city:
  This feature supports navigation within the app and provides detailed trip information, enhancing interactivity and usability.
- Suspense and Lazy loading: This is a performance optimization feature with the lazy and suspense functionality from React.

## Technologies Used

This project was built with the following technologies:

- **React**: A JavaScript library for building user interfaces.
- **React Router**: Handles routing and navigation in single-page applications.
- **Json Server**: A simple, lightweight tool for creating a RESTful API by serving a local JSON file as a database, often used for prototyping or development purposes.
- **React Datepicker**: A reusable and customizable date picker component for React applications, commonly used for selecting dates in forms or application
- **Leaflet and React Leaflet**:

  - **Leaflet**: A lightweight and open-source JavaScript library for creating interactive maps.
  - **React Leaflet**: A React wrapper for Leaflet that allows developers to use Leaflet's mapping capabilities in a React application with declarative components.

- **Vite**: A fast and modern build tool for web development.

## Getting Started

To run this project locally, follow these steps:

### Prerequisites

- Node.js and npm/yarn installed on your machine.
- Clone this repository.

### Installation

1. Install the project dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

## Usage

Once you have installed the dependencies and started the development server, you can use the application as follows:

### Running the Application

1. Start the development server:
   ```bash
   npm run dev
   # or
   yarn dev
   ```
2. Open your browser and navigate to:

   ```bash
   http://localhost:3000
   ```

## Contributing

Contributions are welcome and appreciated! To contribute, follow these steps:

1. **Fork the repository**: Click the "Fork" button at the top of this repository to create a copy of it on your GitHub account.

2. **Clone the repository**: Clone your forked repository to your local machine.
   ```bash
   git clone https://github.com/your-username/rest-countries-api.git
   ```
3. Create a new branch: Create a branch for your feature or bug fix.

   ```bash
   git checkout -b feature-or-bugfix-name
   ```

4. Make changes: Add your changes or new features to the codebase.

5. Commit changes: Commit your changes with a meaningful commit message.
   ```bash
   git commit -m "Description of your changes"
   ```
6. Push changes: Push your changes to your forked repository.
   ```bash
   git push origin feature-or-bugfix-name
   ```

### Guidelines

- Follow the coding style used in the project.
- Write clear, concise commit messages.
- Ensure your code passes all tests and linting checks.
- Keep your pull requests focused and avoid mixing unrelated changes.

Thank you for contributing to this project!
