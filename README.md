# Digital-twin-VR-Framework
This research project explores the fusion of virtual reality and telemanipulation to overcome geographical gaps and revolutionize human interaction. This documentation will guide you through the core stacks, components, setup, and development process.

# Installation:
## Perception stack git: 
https://github.com/maxilar20/ros2_ws.git

## VR stack
https://nextcloud.maeldorne.com/s/wJZZ2sCfpgJJ9qt

## TELETwin 
WIP

# Table of Contents
- [Introduction](#introduction)
- [Core Stacks](#core-stacks)
- [Components](#components)
- [How To Use](#how-to-use)
- [Development Guide](#development-guide)
- [Contributing](#contributing)
- [License](#license)

## Introduction
The project aims to create an open and versatile framework that combines telemanipulation and virtual reality to bridge the gap between remote environments and human interaction. By leveraging depth cameras, Unity3D, and ROS2, this project provides a comprehensive solution for telepresence scenarios.

## Core Stacks
The project consists of three core stacks:
1. **Perception Stack**: Responsible for capturing real-world environments using depth cameras, generating real-time Pointclouds, and managing camera localization.
2. **Virtual Environment Stack**: Utilizes Unity3D and the XR Interaction Toolkit to create an immersive virtual environment for users to interact with.
3. **Manipulation Stack**: Integrates with the TELETwin framework to enable telemanipulation of the real environment through virtual avatars.

## Components
The key components of the project include:
- **Depth Cameras**: Multiple depth cameras capture real-world environments and generate RGB Pointclouds.
- **Unity3D**: Provides the virtual reality environment, offering XR Interaction Toolkit for intuitive user interaction.
- **ROS2**: Used for communication and data exchange between different components of the system.
- **TELETwin Framework**: Enables real-time telemanipulation and integration with Unity3D's XR Interaction Toolkit.

## How To Use
1. **Clone the Repository**: Clone this repository to your local machine.
2. **Install Dependencies**: Follow the instructions in the [Dependencies](/dependencies) directory to install necessary software and packages.
3. **Set Up Depth Cameras**: Configure and connect your depth cameras as outlined in [Depth Cameras Setup](/depth_cameras_setup).
4. **Configure Unity3D Environment**: Set up Unity3D environment and import the necessary assets as described in [Unity3D Setup](/unity3d_setup).
5. **Integrate TELETwin**: Follow the steps in [TELETwin Integration](/teletwin_integration) to integrate the telemanipulation framework.
6. **Run the System**: Start the system by running ROS2 nodes, launching Unity3D virtual environment, and initiating telemanipulation.

## Development Guide
If you're interested in contributing to the project's development, follow these steps:
1. **Fork the Repository**: Fork this repository to your GitHub account.
2. **Clone Your Fork**: Clone your forked repository to your local machine.
3. **Create a Branch**: Create a new branch for your feature or bug fix.
4. **Make Changes**: Implement your changes and ensure your code adheres to the project's coding standards.
5. **Test**: Test your changes thoroughly to ensure functionality and compatibility.
6. **Commit and Push**: Commit your changes, push to your forked repository, and create a pull request.

## Contributing
Contributions to this project are welcome! If you have ideas, improvements, or bug fixes, please submit a pull request. For major changes or new features, it's recommended to discuss the changes first by opening an issue.

## License
This project is licensed under the [MIT License](LICENSE).

