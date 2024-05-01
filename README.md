## Features

- Displays a numbered list of available services for customers to choose from.
- Allows customers to input their phone number, name (if not already a customer), and preferred appointment time.
- Handles cases where the phone number entered doesn't exist by creating a new customer record.
- Creates appointments in the database, associating them with the selected service and customer.
- Outputs a confirmation message with the details of the scheduled appointment.

## Usage

1. Clone the repository to your local machine.
2. Ensure PostgreSQL is installed and running.
3. Set up the database schema by running the provided SQL scripts.
4. Modify the script if necessary to match your database connection details.
5. Execute the script in a Bash environment.

## Prerequisites

- Bash environment
- PostgreSQL

## Database Schema

The script assumes the following database schema:

- **services**: Contains details of available services.
- **customers**: Stores customer information, including name and phone number.
- **appointments**: Records appointments, linking customers with services and appointment times.

## Script Execution

To run the script, execute the following command:

```bash
./salon_appointment.sh
```

Follow the prompts to select a service, provide contact information, and schedule an appointment.