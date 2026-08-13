# IT Service Desk and Ticket Management System

## Project Overview

The IT Service Desk and Ticket Management System is a Python-based application integrated with a MySQL database to manage IT support requests.

The system allows users to create tickets, assign tickets to support agents, update ticket status and priority, search tickets, and generate support insights using SQL queries.

## Key Features

- Create and manage IT support tickets
- Assign tickets to support agents
- Update ticket status and priority
- Search tickets by ID, status, priority, and category
- Track ticket resolution time
- Analyze tickets by status, priority, and category
- Monitor agent workload
- Generate support reports

## Technologies Used

- **Python** — Application logic and ticket management
- **MySQL** — Database for storing users, agents, and tickets
- **SQL** — Data manipulation, searching, aggregation, and reporting
- **mysql-connector-python** — Connecting Python with MySQL
- **Jupyter Notebook** — Development and execution environment

## Database Structure

The system uses three main tables:

### 1. Users

Stores information about employees who raise IT support tickets.

### 2. Agents

Stores information about IT support agents who handle tickets.

### 3. Tickets

Stores IT support request details, including:

- Ticket ID
- User
- Assigned agent
- Issue title
- Description
- Category
- Priority
- Status
- Created time
- Resolved time

## How the System Works

1. A user creates an IT support ticket.
2. The ticket is stored in the MySQL database.
3. A support agent can be assigned to the ticket.
4. The agent can update the ticket status and priority.
5. Users can search tickets using different criteria.
6. Resolved tickets store the resolution time.
7. SQL queries are used to generate support reports and insights.

## Support Reports

The system generates the following support insights:

- Total number of tickets
- Tickets by status
- Tickets by priority
- Tickets by category
- Agent workload
- Average ticket resolution time

## How to Run

### 1. Install Python

Make sure Python is installed on your system.

### 2. Install Required Python Package

Open Command Prompt or terminal and run:

```bash
pip install mysql-connector-python