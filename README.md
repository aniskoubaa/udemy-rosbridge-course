# ROS-Teleoperation-Web-Interface

This repository contains a React-based web application for teleoperating and monitoring a robot using the Robot Operating System (ROS). The web interface allows you to control the robot, visualize the navigation map, and monitor its position, orientation, and velocity. This project is built with ReactJS, a popular JavaScript framework for front-end development.

[![Course](https://img.shields.io/badge/Udemy-Course-blue)](https://www.udemy.com/ros-web-nav/)
[![Discount](https://img.shields.io/badge/Discount-Coupons-green)](https://www.riotu-lab.org/udemy.php)

## Udemy Course

Learn more about this project and the concepts behind it by enrolling in our Udemy course: [ROS Web Navigation](https://www.udemy.com/course/ros-web-nav/).

## Discount Coupons

For occasional time, you can get discount coupons for this course on our website: [RIOTU Lab](https://www.riotu-lab.org/udemy.php).

## Video Overview

Watch video overview on YouTube to help you get started with the project and understand the project scope:

[![ROS for Beginners III: Web-based Navigation with ROSBridge](http://img.youtube.com/vi/cmQ-a8-0TeQ/0.jpg)](http://www.youtube.com/watch?v=cmQ-a8-0TeQ "ROS for Beginners III: Web-based Navigation with ROSBridge")

## Project Overview

The web interface is composed of the following components:

- **About.jsx**: Contains information about the project and its purpose.
- **Body.jsx**: The main body of the web application.
- **Connection.jsx**: Displays the connection status of the robot.
- **Footer.jsx**: The footer section of the web application.
- **Header.jsx**: The header section of the web application.
- **Home.jsx**: The landing page of the web application.
- **Map.jsx**: Displays the navigation map and allows the user to set the robot's goal location.
- **RobotState.jsx**: Displays live information about the robot's position, orientation, and linear/angular velocity.
- **Teleoperation.jsx**: Provides teleoperation controls, including a web-based joystick and an emergency stop button.

## Getting Started

These instructions will help you set up the project on your local machine for development and testing purposes.

### Prerequisites

Before you begin, make sure you have the following software installed on your machine:

- Node.js (v14.x or later)
- npm (v7.x or later)
- ROS (Robot Operating System)
- ROSBridge Package

The course provides complete details on the environment setup process.

### Installing Dependencies

To install the required dependencies, navigate to the project directory and run the following command:

```bash
npm install
```

This command will install all the necessary packages from the package.json file.

### Running the Project

To start the project, navigate to the project directory and run:

```bash
npm start
```

This command will launch the development server, and the web application will be accessible at [http://localhost:3000](http://localhost:3000) in your web browser.

## Contributing

We welcome contributions to this project. Please read the [CONTRIBUTING.md](CONTRIBUTING.md) file for more information on how to contribute, submit pull requests, and report issues.

## License

This project is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International License**. You are free to use, share, and adapt this material for non-commercial purposes, as long as you provide attribution to the original author(s) and the source.

## Acknowledgments

We would like to thank all the contributors and the ROS community for their support and resources that made this project possible.
