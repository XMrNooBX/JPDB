# Project Management Form

## Description
This project is a web-based project management form designed to interact with a database via JsonPowerDB, a powerful REST API for handling and storing project data. The application allows users to input, update, and retrieve project information, such as project ID, name, assigned personnel, assignment date, and deadlines. It connects to the JsonPowerDB API for data operations such as saving new projects and updating existing ones.

The user interface is simple and intuitive, making it easy to manage project data. It is built using HTML, JavaScript, and a backend service (JsonPowerDB API) to handle the actual data storage and retrieval operations.

### Key Features:
- **Retrieve project data**: When a project ID is entered, the system checks whether the project exists and pre-populates the form for editing.
- **Save new projects**: If the project does not exist, users can save a new project to the database.
- **Update existing projects**: Users can update project details using the provided form.
- **Real-time interaction**: The system interacts with the JsonPowerDB backend for real-time data updates.
  
## Benefits of using JsonPowerDB
JsonPowerDB (JPDB) is a fast, efficient, and flexible REST API that provides several advantages:

- **Fast Data Retrieval**: JsonPowerDB allows fast data access and retrieval from the database with minimal latency.
- **No Schema Required**: Unlike traditional databases, JsonPowerDB doesn't require predefined schemas, which gives developers more flexibility.
- **RESTful API**: Provides an easy-to-use REST API interface, making it simple to integrate with web applications like the one developed here.
- **Real-time Database**: JsonPowerDB supports real-time data handling, allowing immediate updates to the database without complex operations.
- **Easy Integration**: Its lightweight and simple API enables quick integration into any application, like this project.

By leveraging JsonPowerDB, the application becomes highly efficient in terms of speed and scalability, while maintaining a clean and simple architecture.

## Release History
- **v1.0.0**: Initial release of the project using J[sonPowerDB. The core functionality includes retrieving and saving project data and functionality for updating existing projects
  - Released on GitHub: [Project Repository v1.0.0]https://github.com/XMrNooBX/JPDB)
## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/XMrNooBX/JPDB
