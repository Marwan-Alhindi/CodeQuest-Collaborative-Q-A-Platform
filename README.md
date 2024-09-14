## Languages and Tools

- **Languages**: Python (for backend), JavaScript (for frontend)
- **Framework**: Flask (lightweight web framework)
- **Database**: SQLite
- **Libraries**: Bootstrap (for UI), Jinja2 (for templating)

# CodeQA Platform: A Question and Answer System

## Overview

This project is a prototype for the CodeQA platform, a community-based question and answer system that allows users to ask and answer questions, vote on content, and earn achievements. The system is built using the Model-View-Controller (MVC) architecture and integrates several key features, including user management, content moderation, and a reward system to enhance engagement.

### Key Features

1. **User Management**:
   - User registration, login, and profile management.
   - Secure authentication and session handling.

2. **Post and Comment Management**:
   - Registered users can create, edit, and remove posts and comments.
   - The system supports tagging of posts for better organization and searchability.
   - Automated spam detection and content validation are integrated.

3. **Voting and Reputation System**:
   - Users can vote on posts and comments, helping surface the best content.
   - Votes influence user reputation and badge awards.

4. **Achievement and Reward System**:
   - Users earn badges based on their contributions to the platform.
   - Achievements are automatically tracked and displayed on user profiles.

5. **Content Moderation**:
   - Administrators can ban users and remove inappropriate content.
   - The platform tracks all moderation actions for auditing purposes.

6. **Notification System**:
   - Users receive notifications for various events such as responses to their posts.

### System Design

- **Model-View-Controller Architecture**: 
   - Ensures clear separation of concerns with the model managing data, the view handling the user interface, and the controller acting as an intermediary.
   
- **AI Integration**: 
   - An AI help system provides real-time suggestions based on platform content and user activity.

- **Scalable Design**:
   - The system is built to handle thousands of transactions and user interactions simultaneously with performance optimizations in place.

### Functional and Non-Functional Requirements

- **Functional Requirements**:
   - Achievement System, AI Help System, Detection System, Tags System, and User Profiles (see [requirements_analysis.pdf](requirements_analysis.pdf)).
   
- **Non-Functional Requirements**:
   - The system is portable across platforms (Windows, macOS, iOS, Android), can handle a high volume of users, and ensures data security with encryption (see [requirements_analysis.pdf](requirements_analysis.pdf)).

### Activity and Sequence Diagrams

For a detailed view of the system’s workflows, refer to the activity and sequence diagrams:
- **Activity Diagrams**: Show the step-by-step flow of key processes like creating posts, logging in, and banning users (see [activity_sequence_diagrams.pdf](activity_sequence_diagrams.pdf)).
- **Sequence Diagrams**: Depict the interactions between system components during specific operations (see [activity_sequence_diagrams.pdf](activity_sequence_diagrams.pdf)).

### Use Case Diagrams

- **Use Case 1: Post**: Registered users can create, edit, and tag posts. The system validates posts before publishing (see [usecase_class_diagram.pdf](usecase_class_diagram.pdf)).
- **Use Case 2: Ban User**: Privileged users can ban others from the platform based on behavior (see [usecase_class_diagram.pdf](usecase_class_diagram.pdf)).

### Test Cases

The system has been thoroughly tested to ensure correct functionality:
- **Post Creation**: Valid and invalid post inputs are tested to ensure proper content validation (see [test_cases.pdf](test_cases.pdf)).
- **Comment Functionality**: The comment system has been tested for character limits, validity, and handling of multiple comments (see [test_cases.pdf](test_cases.pdf)).

### Software Engineering Process

The platform was developed using the **Agile methodology**, promoting iterative development and flexibility in response to changing requirements (see [requirements_analysis.pdf](requirements_analysis.pdf)).
