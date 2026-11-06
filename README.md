# Mini Nature Museum AR

## 1. Project Description

Mini Nature Museum AR is a web-based Augmented Reality application developed as a group assignment.

The application uses marker-based Augmented Reality technology. When the camera detects the Hiro marker, different 3D objects appear on the marker.

Users can view animated 3D objects and interact with selected objects by clicking or tapping them.

## 2. Technologies Used

- HTML
- JavaScript
- A-Frame
- AR.js
- WebGL
- Visual Studio Code

## 3. Main Features

1. Hiro marker-based Augmented Reality.
2. Multiple 3D objects displayed on the marker.
3. Rotating cylinder animation.
4. Bouncing sphere animation.
5. Interactive sphere that changes colour when clicked.
6. Interactive blue box that grows and shrinks when clicked.
7. Apple 3D model.
8. Text labels displayed in the AR scene.
9. Status banner that changes its text and colour when the marker is detected or lost.

## 4. Project Folder Structure

```text
MiniNatureMuseumAR/
│
├── index.html
│
├── models/
│   └── apple/
│       ├── food_apple_01.gltf
│       ├── food_apple_01.bin
│       └── textures/
│           ├── food_apple_01_diff_1k.jpg
│           ├── food_apple_01_nor_gl_1k.jpg
│           └── food_apple_01_rough_1k.jpg
│
└── README.md
```

## 5. How to Run the Application

1. Download or copy the project folder to your computer.
2. Open the project folder using Visual Studio Code.
3. Install the Live Server extension.
4. Open the `index.html` file.
5. Right-click and select **Open with Live Server**.
6. Allow camera permission in the browser.
7. Show the Hiro marker to the camera.
8. View and interact with the 3D objects.

**Note:** To access the application using a mobile phone, host the project using an HTTPS-enabled platform.

An internet connection is required to load the A-Frame and AR.js libraries.

## 6. User Interactions

- Tap the coloured sphere to change its colour.
- Tap the blue box to make it grow.
- Tap the blue box again to return it to its original size.
- Show the Hiro marker to activate the AR scene.
- Move the marker away from the camera to see the status banner change.

## 7. 3D Model Credits

**Model Name:** Food Apple 01

**Creator:** Oliver Harries

**Source:** Poly Haven

**Model Page:** https://polyhaven.com/a/food_apple_01

**Licence:** CC0 1.0 Universal (Public Domain)

The Apple 3D model was downloaded from Poly Haven and is used in this Augmented Reality application. The model files and textures are stored locally in the `models/apple` folder.

No attribution is required under the CC0 licence. Credit is provided here to acknowledge the original creator.
## 8. Group Members

| No. | Student Name         | Student ID   |
| --- | ---------------      | ------------ |
| 1   | [Methwin Maddumage]  | [27106048]   |
| 2   | [Navitha Dulsith]    | [27108865]   |
| 3   | [Pasindu Weerathunga]| [27106044]   |
| 4   | [Dinuja Lakmina]     | [27106054]   |
| 5   | [Nesandu Nimjaya]    | [27109048]   |
| 6   | [Bihandu Hansana]    | [27108122]   |

## 9. Project Information

**Project Name:** Mini Nature Museum AR

**Project Type:** Web-Based Augmented Reality Application

**Module:** Applied Group Project in Emerging Technologies

**Academic Institution:** Academic Institution: University of Plymouth
## 10. Project Links

### GitHub Repository
[View Source Code](https://github.com/Pasindu07/MiniNatureMuseumAR.git)

### Live Application
[Open Mini Nature Museum AR](https://pasindu07.github.io/MiniNatureMuseumAR/)