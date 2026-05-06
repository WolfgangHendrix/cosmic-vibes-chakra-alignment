# 7 Chakra Solfeggio & Binaural Healing

A portable chakra frequency generator web application featuring Solfeggio tones and binaural beat integration for meditation. This project is designed as a Progressive Web App (PWA) with a focus on immersive visual and auditory experiences.

## Project Overview

-   **Type:** Single-page Web Application (PWA).
-   **Core Technologies:**
    -   **HTML5:** Structure and UI elements.
    -   **Vanilla CSS:** Advanced styling including gradients, animations, and responsive layouts.
    -   **Vanilla JavaScript:** Logic for Web Audio API, UI interactions, and state management.
    -   **Web Audio API:** Generates real-time Solfeggio frequencies and binaural beats.
-   **Architecture:** The application is contained entirely within `index.html`, including the CSS and JavaScript. It uses a custom-built audio engine to manage oscillators and gain nodes for seven distinct chakras.

## Key Features

-   **Chakra Frequencies:** Seven dedicated tones (396 Hz to 963 Hz) associated with specific chakras.
-   **Binaural Beats:** Optional brainwave entrainment modes (Delta, Theta, Alpha, Beta, Gamma).
-   **Journey Mode:** Automated sequential activation of chakras for a timed meditation session.
-   **Presets:** Predefined combinations of chakra frequencies (e.g., "The Holy Trinity", "Mental Detox").
-   **Breathing Guide:** A visual aid for rhythmic breathing.
-   **Responsive Design:** Optimized for mobile (PWA), tablet, and desktop viewing.

## Usage & Development

### Running the Project

Since this is a static web application, you can run it by opening `index.html` in any modern web browser.

-   **Local Development:** No build step is required. Simply edit `index.html` and refresh the browser.
-   **PWA:** The `manifest.json` allows the app to be installed on mobile devices and desktop browsers for offline-capable, standalone usage.

### Key Commands

-   **Test:** There are currently no automated tests. Manual verification in a browser is required for UI and audio logic.
-   **Build:** N/A (Source is the distribution).

### Development Conventions

-   **Self-Contained:** The project prioritizes being self-contained in a single HTML file for portability and simplicity.
-   **Web Audio API:** All audio logic is handled in the `script` tag within `index.html`.
-   **Animations:** CSS animations are used extensively for visual feedback (e.g., `chakraPulse`, `energyFlow`).
-   **iOS Compatibility:** Specific handling for iOS audio context initialization and backgrounding is implemented.

## Directory Structure

-   `index.html`: The main entry point containing all HTML, CSS, and JavaScript.
-   `manifest.json`: Configuration for PWA installation.
-   `icon-192.png` & `icon-512.png`: App icons for PWA.
-   `cosmic-vibes-holistic-healing-chakra-alignment-tool_rc02.zip`: A backup/release archive of the project.
