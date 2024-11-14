# Task Sync Hub (TSH)

Task Sync Hub (TSH) is an iOS application designed to streamline task management for owners and agents. TSH allows users to manage appointments, services, and work invoices effectively, enhancing productivity and operational efficiency. This README provides an overview of the database schema, installation instructions, and contribution guidelines.

---

## Features

- **Appointment Management**: Create, update, and track task-related appointments.
- **Invoicing**: Generate and manage work invoices with detailed item listings.
- **Service Listings**: Define and manage services with hourly rates.
- **Agent Interaction**: Enable agents to respond to task assignments, allowing for task acceptance or rejection.

## Database Schema

The TSH app database consists of the following tables:

1. **Company**: Stores company information.
2. **Users**: Manages information about individual users, such as owners and agents.
3. **Appointments**: Tracks appointments for various tasks.
4. **Work_Invoice**: Stores billing details for each appointment.
5. **Work_Invoice_Item**: Lists individual items in a work invoice.
6. **Services**: Maintains service details, including rate and description.
7. **Agent_Response**: Logs agents’ responses to assigned tasks.

For more detailed information, refer to the `DATABASE_DOCUMENTATION.md` file.

## Database Schema

Here is the entity-relationship model (ERD) of the Task Sync Hub database:

![Database Schema](https://github.com/seher-ayesha/task-sync-hub/blob/main/TaskSyncHub_Database_Schema_drawio.png)

## Future Enhancements

- **User Notifications:** Notify agents and owners of task updates.
- **Enhanced Reporting:** Provide detailed reports for task analytics.
- **Role-Based Access Control:** Implement different permissions for owners and agents.


## Installation

1. **Clone the Repository**: Clone the project repository from GitHub.
   
   ```bash
   git clone https://github.com/seher-ayesha/TaskSyncHub.git


   
## Credits
Developed by [Seher Ayesha](https://github.com/seher-ayesha)

## License

This project is licensed under the MIT License - please see the [LICENSE.md](https://github.com/seher-ayesha/task-sync-hub/blob/main/LICENSE.md) file for details.

