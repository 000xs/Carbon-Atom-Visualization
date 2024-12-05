# Carbon Atom Visualization

Explore the intricate structure of a Carbon atom in an immersive 3D environment. This project uses **Three.js** to render the atom's components, allowing users to visualize the nucleus, protons, neutrons, and orbiting electrons dynamically.

## Features

- **3D Visualization**: Interactive 3D rendering of a Carbon atom with a nucleus and orbitals.
- **Realistic Animation**: Protons, neutrons, and electrons move dynamically within the scene.
- **Responsive Design**: The application adjusts seamlessly to different screen sizes for optimal user experience.
- **OrbitControls Integration**: Allows users to pan, zoom, and rotate the view interactively.
- **Legend Panel**: Provides a clear identification of protons, neutrons, and electrons.

## Project Setup

### Prerequisites
- A modern web browser with WebGL support.
- Internet access to load external dependencies.

### How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/carbon-atom-visualization.git
   ```
2. Navigate to the project directory:
   ```bash
   cd carbon-atom-visualization
   ```
3. Open the `index.html` file in a web browser:
   - Double-click `index.html` or serve the file using a local server:
     ```bash
     python -m http.server 8000
     ```
     Visit `http://localhost:8000` in your browser.

## Technologies Used

- **HTML5**: Provides the structural markup for the webpage.
- **CSS3**: Styles the layout, including the legend and responsive design.
- **JavaScript (ES6)**: Implements the 3D rendering, animations, and interactions.
- **Three.js**: A 3D library for rendering the atom and its components.
- **OrbitControls.js**: Enables interactive camera movements.

## Project Structure

```plaintext
.
├── index.html          # Main HTML file for the project
├── styles.css          # Contains CSS styling for the layout
├── README.md           # Project documentation
└── scripts.js          # JavaScript code for atom rendering and animations
```

## Visualization Details

### Components
- **Protons**: Represented in red.
- **Neutrons**: Represented in blue.
- **Electrons**: Represented in green, dynamically orbiting the nucleus.

### Nucleus
The nucleus contains six protons and six neutrons, arranged randomly to simulate real atomic behavior.

### Orbitals
- **Inner Orbit**: Contains two electrons.
- **Outer Orbit**: Contains four electrons, each positioned at 90-degree angles.

## Live Demo
Access the live project [here](#).

## Future Enhancements

- Add support for visualizing atoms of other elements.
- Introduce educational tooltips for detailed descriptions.
- Add UI controls for customizing the visualization (e.g., electron speed).

## License

This project is licensed under the [MIT License](LICENSE).

---

 
