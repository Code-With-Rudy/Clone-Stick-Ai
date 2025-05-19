# Clone Stick AI

![Clone Stick AI](https://github.com/Code-With-Rudy/Clone-Stick-Ai/blob/main/Clone%20Stick.png)

## About

Clone Stick AI is an advanced motion tracking application that creates stunning visual representations of your movements in real-time. Using AI-powered pose estimation technology, the app mirrors your movements with customizable visual effects, providing a unique interactive experience.

Developed by Rudranil, this application combines computer vision, artificial intelligence, and creative visualization to transform ordinary movements into extraordinary digital art.

## Features

### 🤖 AI-Powered Pose Detection
- Accurate real-time body tracking using MediaPipe technology
- Precise landmark detection for smooth motion visualization
- Works with various lighting conditions and environments

### ✨ Visual Effects
- Multiple effect options:
  - **Glow**: Soft luminous effect around your pose
  - **Neon**: Bright, vibrant outlines with blur effect
  - **Rainbow**: Colorful multi-hued visualization that changes across body parts

### 🔄 Real-time Motion Mirroring
- Create a digital clone that mirrors your movements
- Instant response with minimal latency
- Adjustable quality settings for different hardware capabilities

### 📊 3D Pose Visualization
- View your movements from multiple perspectives in a 3D space
- Interactive 3D representation of your body's position
- Real-time updates synchronized with your movements

### 🎨 Customization Options
- Choose from multiple color schemes
- Adjust effect quality (Low, Normal, High)
- Switch between internal and external cameras

### 🖥️ User-Friendly Interface
- Clean, modern dark-themed UI
- Fullscreen mode for immersive experiences
- Simple controls for easy operation

## Screenshots

![Main Interface](https://your-screenshot-url-1-here.png)
![Effect Demo](https://your-screenshot-url-2-here.png)
![3D Visualization](https://your-screenshot-url-3-here.png)

## System Requirements

- **Operating System**: Windows 10 or later (64-bit)
- **Processor**: Intel Core i5 or equivalent (quad-core recommended)
- **Memory**: 8GB RAM minimum (16GB recommended)
- **Graphics**: Dedicated GPU recommended for better performance
- **Camera**: Working webcam (internal or external)
- **Screen Resolution**: 1280x720 or higher
- **Storage**: At least 500MB of free disk space

## Dependencies

The application uses the following libraries:
- OpenCV (cv2)
- MediaPipe
- NumPy
- Matplotlib
- Tkinter
- PIL (Pillow)
- Threading

## Installation

### Option 1: Download the Executable
1. Go to the [Releases](https://github.com/Code-With-Rudy/CloneStickAI/releases) section
2. Download the latest `CloneStickAI-Setup.exe`
3. Run the installer and follow the instructions
4. Launch the application from the Start menu or desktop shortcut

### Option 2: Run from Source
1. Clone this repository:
   ```
   git clone https://github.com/Code-With-Rudy/CloneStickAI.git
   ```
2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Run the application:
   ```
   python clone_stick_app.py
   ```

## Usage

1. Launch Clone Stick AI
2. Select your camera source (Internal or External)
3. Choose your preferred visual effect (Glow, Neon, Rainbow)
4. Adjust quality settings according to your hardware capabilities
5. Click "Start" to begin the cloning experience
6. Move around to see your clone mirror your movements
7. Use the "Change Color" button to cycle through different color schemes
8. Toggle fullscreen mode for a more immersive experience

## Development

### Project Structure
```
CloneStickAI/
├── clone_stick_app.py       # Main application file
├── requirements.txt         # Python dependencies
├── README.md                # This file
├── LICENSE                  # License information
└── assets/                  # Application assets
    └── images/              # Images for the application
```

### Building from Source
To build the executable yourself:
1. Install PyInstaller:
   ```
   pip install pyinstaller
   ```
2. Run the build command:
   ```
   pyinstaller --onefile --windowed --icon=assets/icon.ico clone_stick_app.py
   ```
3. Find the executable in the `dist` folder

## Troubleshooting

### Common Issues

1. **Camera not detected**
   - Ensure your webcam is properly connected
   - Try switching between Internal/External camera options
   - Check if another application is using the camera

2. **Performance is slow**
   - Lower the quality setting to "Low"
   - Close other resource-intensive applications
   - Ensure you meet the minimum system requirements

3. **Application crashes on startup**
   - Verify that all dependencies are correctly installed
   - Update your graphics drivers
   - Ensure you have sufficient permissions on your system

## Contributing

Contributions are welcome! If you'd like to contribute to this project:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add some amazing feature'`)
5. Push to the branch (`git push origin feature/amazing-feature`)
6. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- MediaPipe team for their excellent pose estimation library
- All the users who provided feedback during development
- Special thanks to the open-source computer vision community

## Author

**Rudranil** - *Project Creator*

- [GitHub]([https://github.com/your-username](https://github.com/Code-With-Rudy))
- [LinkedIn]([https://linkedin.com/in/your-profile](https://in.linkedin.com/in/rudranil-goswami-a94298329))
- [Instagram](**https://your-website.com**)

---

<p align="center">
  Made with ❤️ by Rudranil
</p>
