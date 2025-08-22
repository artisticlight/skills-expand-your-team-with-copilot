# GitHub Issue Templates for Teachers

This directory contains GitHub issue template forms designed to help teachers easily request changes to the High School Management System. Each template provides structured forms that capture enough detail for the Copilot coding agent to implement changes without requiring additional clarification.

## Available Templates

### 🏫 Add New Activity (`add_activity.yml`)
For requesting new extracurricular activities to be added to the system.
- **Fields**: Activity name, description, schedule, capacity, supervising teacher
- **Use case**: Adding new clubs, sports, academic teams
- **Auto-assigns**: @copilot

### ✏️ Modify Existing Activity (`modify_activity.yml`)
For requesting changes to existing activities.
- **Fields**: Activity selection, modification type, new details, reason for change
- **Use case**: Schedule changes, capacity adjustments, description updates
- **Auto-assigns**: @copilot

### 🐛 Bug Report (`bug_report.yml`)
For reporting issues with the system.
- **Fields**: Bug description, steps to reproduce, expected vs actual behavior, severity
- **Use case**: Login issues, registration problems, display errors
- **Auto-assigns**: @copilot

### ✨ Feature Request (`feature_request.yml`)
For requesting new functionality.
- **Fields**: Feature description, business justification, use cases, priority
- **Use case**: New capabilities, UI improvements, reporting features
- **Auto-assigns**: @copilot

### 👥 User Management Request (`user_management.yml`)
For teacher account and permission changes.
- **Fields**: Request type, user details, roles, security considerations
- **Use case**: New teacher accounts, permission changes, account deactivation
- **Auto-assigns**: @copilot

### ⚙️ System Configuration (`system_configuration.yml`)
For system settings and maintenance requests.
- **Fields**: Configuration type, current/desired state, risk assessment, rollback plan
- **Use case**: Performance optimization, security settings, system maintenance
- **Auto-assigns**: @copilot

## Template Features

All templates include:
- **Clear problem descriptions** with structured data entry
- **Acceptance criteria** to define completion requirements  
- **Technical context** for developers including:
  - System architecture details
  - Key file locations
  - Implementation hints
  - Database schema information
- **Business justification** for prioritization
- **Risk assessment** and rollback considerations
- **Automatic assignment** to @copilot for streamlined processing

## Configuration

The `config.yml` file:
- Disables blank issues to encourage use of templates
- Provides contact links for questions and discussions
- Organizes template presentation in GitHub's issue creation UI

## Usage for Teachers

1. Go to the repository's Issues tab
2. Click "New Issue"
3. Select the appropriate template for your request
4. Fill out all required fields with detailed information
5. Submit the issue - it will automatically be assigned to @copilot

The structured forms ensure that all necessary information is captured upfront, reducing back-and-forth communication and enabling faster implementation by the coding agent.