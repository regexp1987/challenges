
# Simple Kanban API

### Problem
This project is a web-service which exposes a REST API for a Kanban application: it allows Users to manage Tasks' progression through a Project.

Users can:
- Create Projects
- Add and edit Tasks
- Invite other users to the team and remove them

A Project and its team can only be modified by their creator.

A team member, as well as the creator, can create and edit Tasks.

The creator User is not considered a team member.

### API Specification
API Specification is provided in the `./swagger.yml` file. It follows the Swagger 2.0 convention.

### Implementation
These are the implementation constraints to adhere to:

- The application can be implemented in any language and platform; feel free to choose the tech you are most comfortable with.
- The application must expose an API as per above provided specs. Any unmentioned aspect can be treated as you please (eg: persistence).
- Tests are not mandatory, but highly appreciated.
- Instruction for starting up the application must be provided. Althrough not mandatory, we strongly recommend the use of Docker containers.

### Submission
Implemented code can be submitted via email to the address `paolo.farinella@superscommesse.it` as single `.zip` file via wetransfer.

### Questions
If you have any questions regarding the challenge, please open an issue on this repository specifying the challenge name.

Good luck with your challenge!

ASAP Dev Team
