# Planter :seedling: 

## About the Team
We are a team of 4 members working together on this project:
| Sarahana B.  | Hannah L.    | Al-Janat O. | Ethan W.   |
|:------------:|:------------:|:-----------:|:----------:|
| **Role 1**   |  **Role 2**  |  **Role 3** | **Role 4** |



## Project Overview
**What are we building?**  
This project provides a planner and guidance system for plant care, helping users track when to water their plants. Initially designed for houseplants, the application will have the structure to later expand to support small garden management and advanced plant care.

**Who is this for?**  
This project is for plant owners looking for an easy way to manage their plant care routine, with a primary focus on newer owners who need guidance. While initially tailored for houseplant enthusiasts, future expansions will accommodate small garden caretakers.

**Why are we doing this?**  

Our team is passionate to develop this application and saw a need for a better plant care management tool. We aim to simplify tracking watering schedules and care routines for houseplants and small gardens, helping users keep their plants healthy with ease.

## Table of Contents
  - [General Information](#general-information)
  - [Technologies Used](#technologies-used)
  - [Features](#features)
  - [Screenshots](#screenshots)
  - [Setup](#setup)
  - [Usage](#usage)
  - [Project Status](#project-status)
  - [Room for Improvement](#room-for-improvement)
  - [Acknowledgements](#acknowledgements)
<!-- * [License](#license) -->


## General Information
 <img src="lib/fillerLogo.png" alt="App Logo" width="200"/>

 >Optional: what’s missing from your project (expertise, users, additional developers, money☺, etc) that you wish you had.


## Technologies Used

Below is a list of the technologies we plan to use for our plant care planner and guidance system. Each technology is hyperlinked to its official documentation or a relevant webpage for further reference.

### Core Technologies
- **[OpenAI ChatGPT API](https://platform.openai.com/docs/api-reference)**: We will use the ChatGPT API to provide users with intelligent guidance on plant care, troubleshooting, and personalized recommendations.
  
- **[Plant Database API](https://example.com/plant-database-api)**: This API will serve as the backbone of our application, providing detailed information about various plants, including watering schedules, sunlight requirements, and care tips. *(Link is to potential API option, finalized API option TBD.)*

### Version Control and Collaboration
- **[Bitbucket](https://bitbucket.org/)**: Bitbucket will serve as our Git repository hosting service, providing a centralized location for code storage and collaboration.

- **[GitKraken](https://www.gitkraken.com/)**: GitKraken will be used as our Git client, offering an intuitive interface for managing repositories, branches, and pull requests.

### Project Management
- **[Jira](https://www.atlassian.com/software/jira)**: Jira will be used for project management, helping us track tasks, manage sprints, and ensure timely delivery of features.

## Features
Below are the initial features we plan to implement in the first sprint. Each feature is described in detail, including its purpose, who or what uses it, and the corresponding user stories.



### 1. **User Registration and Authentication**
- **Description**: Allows users to create an account and log in securely. This feature ensures that each user’s plant data is private and accessible only to them.
- **Used By**: Plant owners (users) who want to track their plant care routines.
- **User Stories**:
  - As a new user, I want to create an account so that I can save my plant care data.
  - As a returning user, I want to log in securely so that I can access my plant care dashboard.


### 2. **Plant Profile Creation**
- **Description**: Enables users to add plants to their profile by entering details such as plant type, name, and care requirements (e.g., watering frequency, sunlight needs).
- **Used By**: Plant owners who want to track specific plants in their collection.
- **User Stories**:
  - As a plant owner, I want to add a plant to my profile so that I can track its care schedule.
  - As a user, I want to input my plant’s care requirements so that I can receive personalized reminders.


### 3. **Watering Schedule Reminders**
- **Description**: Sends users reminders via email or SMS when it’s time to water their plants. The reminders are based on the care requirements entered during plant profile creation.
- **Used By**: Plant owners who need help remembering when to water their plants.
- **User Stories**:
  - As a busy plant owner, I want to receive reminders to water my plants so that I don’t forget.
  - As a user, I want to customize the frequency of watering reminders so that they match my plant’s needs.


### 4. **Interactive Plant Care Dashboard**
- **Description**: Provides users with a visual dashboard where they can view all their plants, upcoming care tasks, and progress over time (e.g., growth milestones).
- **Used By**: Plant owners who want an overview of their plant care routines.
- **User Stories**:
  - As a user, I want to see a dashboard of all my plants so that I can manage them in one place.
  - As a plant owner, I want to view upcoming care tasks so that I can plan my week.

### 5. **Chat-Based Plant Care Assistant**
- **Description**: Integrates the ChatGPT API to provide users with conversational guidance on plant care, troubleshooting, and tips. Users can ask questions like, “Why are my plant’s leaves turning yellow?”
- **Used By**: Plant owners who need advice or troubleshooting help.
- **User Stories**:
  - As a new plant owner, I want to ask questions about plant care so that I can learn how to keep my plants healthy.
  - As a user, I want to receive personalized plant care tips so that I can improve my plant care routine.


### 6. **Plant Database Integration**
- **Description**: Pulls plant care information (e.g., watering schedules, sunlight requirements) from a plant database API to auto-fill care details when users add a new plant.
- **Used By**: Plant owners who want accurate and detailed care information for their plants.
- **User Stories**:
  - As a user, I want to select my plant type from a database so that I don’t have to manually enter care details.
  - As a plant owner, I want to access accurate care information so that I can provide the best care for my plants.


### 7. **Progress Tracking with Visualizations**
- **Description**: Uses Chart.js to display visual progress reports, such as watering history, growth milestones, and overall plant health trends.
- **Used By**: Plant owners who want to track the long-term health and progress of their plants.
- **User Stories**:
  - As a user, I want to see a history of my plant care activities so that I can track my progress.
  - As a plant owner, I want to visualize my plant’s growth over time so that I can celebrate milestones.


### 8. **Responsive Mobile-Friendly Design**
- **Description**: Ensures the application is fully responsive and works seamlessly on mobile devices, allowing users to manage their plants on the go.
- **Used By**: Plant owners who prefer using their smartphones for managing tasks.
- **User Stories**:
  - As a mobile user, I want to access the plant care app on my phone so that I can manage my plants anytime, anywhere.
  - As a user, I want the app to be easy to use on a small screen so that I can quickly check my plant care tasks.


### 9. **Task Completion Tracking**
- **Description**: Allows users to mark care tasks (e.g., watering, fertilizing) as completed and tracks their completion history.
- **Used By**: Plant owners who want to stay organized and ensure all care tasks are completed.
- **User Stories**:
  - As a user, I want to mark tasks as completed so that I can keep track of what I’ve done.
  - As a plant owner, I want to see a history of completed tasks so that I can ensure my plants are well cared for.


### 10. **Multi-Device Synchronization**
- **Description**: Uses Firebase to synchronize user data across multiple devices, ensuring that users can access their plant care information from any device.
- **Used By**: Plant owners who use multiple devices (e.g., phone, tablet, computer).
- **User Stories**:
  - As a user, I want my plant care data to sync across devices so that I can access it from anywhere.
  - As a plant owner, I want changes made on one device to reflect on all my devices so that I stay up to date.

---

### Summary of User Stories
| Feature                     | User Stories                                                                 |
|-----------------------------|------------------------------------------------------------------------------|
| User Registration           | Create account, log in securely                                             |
| Plant Profile Creation      | Add plants, input care requirements                                         |
| Watering Schedule Reminders | Receive reminders, customize frequency                                      |
| Interactive Dashboard       | View all plants, see upcoming tasks                                         |
| Chat-Based Assistant        | Ask questions, receive tips                                                 |
| Plant Database Integration  | Select plant type, access accurate care info                                |
| Progress Tracking           | View history, visualize growth                                              |
| Mobile-Friendly Design      | Access on mobile, easy-to-use interface                                     |
| Task Completion Tracking    | Mark tasks as completed, view history                                       |
| Multi-Device Synchronization| Sync data across devices, stay up to date                                   |

## Screenshots
![Example screenshot](./img/screenshot.png)


## Setup
What are the project requirements/dependencies? Where are they listed? A requirements.txt or a Pipfile.lock file perhaps? Where is it located?

Proceed to describe how to install / setup one's local environment / get started with the project.


## Usage
How does one go about using it?
Provide various use cases and code examples here.

`write-your-code-here`


## Project Status
Project is: _in progress_ / _complete_ / _no longer being worked on_. If you are no longer working on it, provide reasons why.


## Room for Improvement
Include areas you believe need improvement / could be improved. Also add TODOs for future development.

Room for improvement:
- Improvement to be done 1
- Improvement to be done 2

To do:
- Feature to be added 1
- Feature to be added 2
