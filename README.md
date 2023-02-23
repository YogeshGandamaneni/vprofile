# DevOps Project - Continuous Integration of Vprofile Project using Jenkins, Nexus, SonarQube and Slack

This is a DevOps project for _Continuous Integration_ of vprofile project using Jenkins, Nexus, SonarQube and Slack.

[Link](https://github.com/durrezahmed/vprofile-project-devops) for vprofile app repository.

## Tools used in the Project:

- **AWS EC2** - Compute Resource

- **Jenkins** - Continuous Integration Server

- **Git and GitHub** - Version Control System

- **Maven** - Build Tool

- **Checkstyle** - Code Analysis Tool

- **Nexus** - Artifact / Software Repository

- **SonarQube** - Code Analysis Server

- **Slack** - Notifications

## Jenkins Plugins used in the Project:

- **Maven Integration** (Build Tools)

- **GitHub Integration** (Build Triggers)

- **Nexus Artifact Uploader** (Artifact Uploaders)

- **SonarQube Scanner** (Build Reports)

- **Slack Notification** (Build Notifiers)

- **Build Timestamp** - (Build Wrappers)

## Services Ports:

- **Jenkins Server** - `8080`

- **Nexus Server** - `8081`

- **SonarQube Server** - `80`

  ( default port for SonarQube Server is `9000` , port `80` is used because a Nginx Server is configured to redirect the request to port `9000` )

## Usage (Flow of Execution):

1. Login to AWS Account - [Link](https://aws.amazon.com/marketplace/management/signin) to Login to your AWS Account.

2. Create Key Pair

3. Create Security Groups

   a. Jenkins, Nexus and Sonarqube

4. Create EC2 Instances with Userdata

   a. Jenkins, Nexus and Sonarqube

5. Post Installation

   a. Jenkins Setup and Plugins

   b. Nexus Setup and Repository Setup

   c. SonarQube Login Test

6. Git and GitHub

   a. Create a GitHub Repository and Migrate Code

   b. Integrate GitHub Repository with VS Code and Test it

7. Build Job with Nexus Integration

8. Github Webhook Setup

9. SonarQube Server Integration Stage

10. Nexus Artifact upload Stage

11. Slack Notification
