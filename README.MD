# Destroyers Strength & Conditioning Tracker

## Overview

The **Destroyers Strength & Conditioning Tracker** is a standalone web application designed to help track the strength progress of the Portsmouth Destroyers American Football Team. It allows players to submit their strength metrics (e.g., weight, bench, squat, deadlift), and coaches to view the weekly progress of the entire team. This project is implemented using **Node.js**, **Express**, and basic web technologies such as **HTML**, **CSS**, and **JavaScript**.

## Features

- **Player Submissions**: Players can input their name, weight, position, and strength metrics.
- **Weekly Overview**: Coaches can view all player submissions and filter results by position.
- **Data Export**: Weekly data can be exported in JSON format with password protection.
- **Reset Mechanism**: Data is cleared at the end of each week after export.

## Project Structure

```
strength-tracker/
├── assets/
│   ├── main.css
│   ├── main.jss
│   └── favico/
│       ├── android-chrome-192x192.png
│       ├── android-chrome-512x512.png
│       ├── apple-touch-icon.png
│       ├── favicon-16x16.png
│       ├── favicon-32x32.png
│       ├── favicon.ico
│       ├── site.webmanifest
├── index.html
├── server.js
├── package.json
├── package-lock.json
├── .env
└── README.md
```

### Key Files and Directories

- **`assets/`**: Contains front-end assets such as CSS, JavaScript, and favicon files.
- **`index.html`**: The primary interface for submitting and viewing strength data.
- **`server.js`**: Back-end logic handling API routes, data processing, and file operations.
- **`.env`**: Environment configuration file (e.g., export password).

## Setup Instructions

### Prerequisites

- **Node.js** (v16 or later recommended)
- **npm** (Node Package Manager)

### Installation

1. **Clone the repository**:

   ```bash
   git clone
   cd Destroyers-Strength-Tracker
   ```

2. **Install dependencies**:

   ```bash
   npm install
   ```

3. **Configure environment variables**:

   - Create a `.env` file in the root directory:

     ```env
     EXPORT_PASSWORD=your_secret_password
     ```

4. **Start the application**:

   ```bash
   node server.js
   ```

5. **Access the application**:

   - Open your browser and navigate to `http://localhost:3000/strength-tracker.html`.

## Usage

1. **Submit Strength Data**:

   - Players can enter their strength metrics (e.g., weight, bench, squat, deadlift).
   - Data is saved temporarily until the end of the week.

2. **View Weekly Results**:

   - Coaches can access the weekly overview and filter results by player position.

3. **Export Weekly Data**:
   - Enter the correct password to download the data as a JSON file.

## Contributing

Contributions are welcome! Feel free to fork the repository, submit a pull request, or open an issue with your suggestions or bug reports.
