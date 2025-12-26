# 2D Gallery with Depth Effect

A lightweight web-based interactive gallery that displays images in a dynamic 2D space with a depth effect. The project uses **Three.js** to render image planes and a **JSON-driven** approach to manage data.

## 📋 Project Overview

This project visualizes botanical data by loading images and metadata from a local JSON file. It creates an interactive environment where users can:
* **Explore:** Navigate through a cloud of images using mouse dragging.
* **Interact:** Hover over images to see their scientific names via a custom tooltip.
* **Zoom:** Use the mouse wheel to move closer or further away from the collection.

## 🛠️ Technologies Used

* **HTML5 &amp; CSS3:** For the basic structure and tooltip styling.
* **JavaScript (ES6+):** For logic and asynchronous data fetching.
* **Three.js:** A 3D library used here to create the 2D plane environment and raycasting interaction.

## 📂 File Structure

* `index.html`: The main entry point containing the Three.js logic and styles.
* `db.json`: The database containing scientific names and image references.
* `/images`: A directory containing the plant images (e.g., `Setaria viridis.png`).

## 🚀 How to Run

1.  **Prepare the folder:** Ensure your `index.html`, `db.json`, and the `images/` folder are in the same directory.
2.  **Use a Local Server:** Because the project fetches data from `db.json`, it must be run through a local web server (like Live Server in VS Code, Python's `http.server`, or Node.js `http-server`).
3.  **Open in Browser:** Access the local server URL (usually `http://localhost:5500`) to view the gallery.

## 📖 Data Documentation

The project relies on a specific structure in `db.json`:
* `scientific_name`: Displayed when hovering over an image.
* `reference_picture_link`: The filename located inside the `/images` folder.

## 👨‍💻 Author

**[Rubens Braz](https://rubensbraz.com/)**
