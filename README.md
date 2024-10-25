# VREVAL Participate

## Overview

**VREVAL Participate** is the desktop application that allows participants to interact with surveys created in the **VREVAL Platform** web application. Built using the Unity Engine, this application allows users to explore 3D virtual environments and complete interactive tasks such as Annotation, AB Testing, and Wayfinding, as part of pre-occupancy evaluations.

The application communicates with the **VREVAL Platform** via its REST API, retrieving survey data, and submitting participant responses.

## Features

- **3D Environment Exploration**: Participants can navigate and interact with 3D virtual environments.
- **Interactive Tasks**: Complete various tasks such as:
  - **Annotation**: Mark locations of interest in the 3D environment.
  - **AB Testing**: Choose between different virtual environment configurations.
  - **Wayfinding**: Navigate to a specific landmark or point of interest.
- **Seamless Integration with VREVAL Platform**: Fetches survey data and submits results via the platform's REST API.

## Getting Started

### Prerequisites

- Unity Engine (version 2021.3 or later recommended)
- REST API endpoint from **VREVAL Platform** to retrieve survey data

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/vreval-participate.git
   cd vreval-participate
   ```

2. **Open the project in Unity:**
   - Open the Unity Hub, click on "Add", and navigate to the `vreval-participate` folder to open the project.

3. **Configure the REST API Endpoint:**
   - In the Unity Editor, open the `APIConfig` file located in `Assets/Scripts/`.
   - Set the base URL of the REST API for the **VREVAL Platform**.

4. **Build the Application:**
   - In Unity, go to `File > Build Settings`.
   - Choose your target platform (Windows, macOS, etc.).
   - Click on "Build" to compile the application.

5. **Run the Application:**
   - After building, run the generated executable to start the survey participation experience.

### Usage

- Upon launching the application, participants will be prompted to connect to the **VREVAL Platform** and retrieve their assigned surveys.
- Participants can navigate through the 3D environment, complete tasks, and submit their results.

## Testing

To run the application in the Unity Editor and simulate survey participation:
1. Open the Unity project in the Unity Editor.
2. Hit the "Play" button to simulate the desktop application environment.
3. Test different tasks (Annotation, AB Test, Wayfinding) using sample 3D environments.

## Contributing

Contributions are welcome! Please fork the repository and submit pull requests for new features, bug fixes, or improvements.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
