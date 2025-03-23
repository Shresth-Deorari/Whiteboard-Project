# Whiteboard Project

A dynamic web-based whiteboard application that allows users to create, edit, and share drawings with a natural hand-drawn feel.
## 🎨 Overview

Whiteboard Project is an interactive canvas application that provides a seamless drawing experience with a natural, hand-drawn aesthetic. Built with modern web technologies, it offers a comprehensive set of tools for creative expression and collaboration.

## ✨ Features

- **Free-hand Drawing**: Create fluid, natural drawings with pressure sensitivity support
- **Hand-drawn Aesthetic**: Integration with Rough.js to give drawings an authentic sketch-like appearance
- **Shape Tools**: Easily create lines, rectangles, ellipses with customizable properties
- **Text Support**: Add and edit text boxes anywhere on the canvas
- **Advanced Controls**:
  - Eraser tool for precise corrections
  - Unlimited undo/redo capabilities powered by Context API
  - Selection tool to modify existing elements
- **Export Functionality**: Save your creations as PNG images
- **Responsive Design**: Works across devices with different screen sizes

## 🛠️ Technologies Used

- React.js
- HTML5 Canvas
- Rough.js
- Context API for state management
- Modern JavaScript (ES6+)

## 💡 Implementation Challenges & Solutions

### Undo/Redo Functionality
Implemented a robust history tracking system using React's Context API to maintain the state of the canvas at different points in time, enabling seamless undo and redo operations.

### Eraser Tool
Created a custom solution for detecting intersections between the eraser path and existing elements on the canvas, with special handling for different element types.

### Text Component Erasure
Developed a specialized approach to handle text element erasure, which required different logic than shape-based elements due to their complex rendering properties.

## 📦 Installation & Setup

### Clone the repository
```
git clone https://github.com/Shresth-Deorari/Whiteboard-Project.git
```

### Navigate to project directory
```
cd Whiteboard-Project
```

### Install dependencies
```
npm i install
```

### Start development server
```
npm start
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.


1. Fork the repository
   
2. Create your feature branch
```
git checkout -b feature/amazing-feature
```

3. Commit your changes
```
git commit -m 'Add some amazing feature'
```

4. Push to the branch
```
git push origin feature/amazing-feature
```

5. Open a Pull Request

## 📧 Contact

Shresth Deorari - [GitHub](https://github.com/Shresth-Deorari)

Email: shresthdeorari38@gmail.com
