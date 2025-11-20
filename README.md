CSS3 Neurobrutalism Mega-Visualizer 🎨⚡

A high-contrast, interactive playground designed to decode CSS3 properties for everyone—from 8-year-olds to seasoned developers. Built with a raw Neurobrutalism aesthetic, this tool provides a tactile way to learn, test, and generate code for modern web styling.

(Replace this link with a real screenshot of your app)

🚀 Core Mission

To demystify CSS by making it tangible. Instead of reading documentation, you manipulate the "Stage" directly.
This app covers everything from the basics (Box Model) to the bleeding edge (Container Queries, Cascade Layers, and Logical Properties).

🧠 Design Philosophy: Neurobrutalism

This tool isn't just functional; it's a statement.

Raw Layouts: Asymmetric grids and visible borders.

High Contrast: Neon greens, hot pinks, and stark blacks.

Hard Shadows: Unblurred, offset shadows for a tactile feel.

Bold Typography: Monospaced fonts for a code-native look.

✨ Key Features

1. The Mega-Database 📚

150+ Properties: Categorized into Box Model, Flexbox, Grid, Typography, Effects, Transforms, Interactivity, and Animations.

EL5 Explanations: Simple, "Explain Like I'm 5" descriptions for every property.

Smart Context: The visualizer adapts based on what you select (e.g., switching to a grid layout when testing grid-template-columns).

2. Advanced Logic Engines ⚙️

Dependency Alerts: Selecting justify-content without display: flex? The app warns you and offers a "Fix It" button.

Context Awareness: Tracks parent container styles (position, display) to ensure child properties (like z-index or flex-grow) behave correctly.

Range Logic: Smart sliders that switch between pixels, percentages, and degrees based on the property type.

3. Multi-Framework Code Generator 💻

Instantly translate your visual styles into code for your stack:

Standard CSS

Vanilla JavaScript (DOM API)

React (Inline Styles)

TypeScript (Typed Objects)

Angular (Template Binding)

Tailwind CSS v4 (Smart utility conversion + arbitrary values)

Bootstrap 5 (Utility mapping)

4. Responsive Design Lab 📱

Viewport Controls: One-click resizing for Mobile, Tablet, and Desktop breakpoints.

Responsive Guide: Built-in cheat sheet for standard breakpoints and recommended spacing/typography scales.

Container Queries: Drag-to-resize handles to test @container rules in real-time.

5. Developer Tools 🛠️

Live Measuring Scale: Visual dimension markers with pixel-to-REM conversion.

Ghost Mode: See the original position of elements during transforms.

Grid & Pattern Overlays: Visualize transparency and alignment.

📦 Installation & Usage

This project follows the Single-File Mandate. There are no build steps, no npm install, and no backend.

Download: Save the index.html file.

Run: Double-click index.html to open it in any modern browser (Chrome, Firefox, Edge, Safari).

Edit: Open the file in VS Code or Notepad to tweak the internal React code directly.

Tech Stack

React 18 (via CDN)

Tailwind CSS (via CDN)

Babel (via CDN for in-browser JSX compilation)

🤝 Contributing

This visualizer is a self-contained educational tool. If you want to add more properties:

Open index.html.

Locate the BASE_DATA array in the JavaScript section.

Add your new property object following the existing schema:

{
  name: "your-property",
  category: "Category Name",
  type: "select | length | color",
  options: ["val1", "val2"], // if select
  def: "default-value",
  desc: "Simple description."
}


📄 License

Free for educational use and modification. Go build something awesome!