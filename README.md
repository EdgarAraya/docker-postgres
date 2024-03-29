## Database Setup

1. Open your terminal in the BD (Database) folder.
2. Run the command: `docker-compose up`
   If you prefer not to see terminal status, use: `docker-compose up -d`.
3. Open your web browser and go to `localhost:5050`.
4. Fill in the requested fields with the following credentials:
   - User/Email: admin@admin.com
   - Password: root
   Note: You can replace these credentials in the `Docker-compose.yaml` file.
5. To stop the containers, run the command: `docker-compose down`.

Alternatively, you can use Docker Desktop and load the image directly.

## Creating a Connection

Upon entering pgAdmin:
- Use the container name from the Docker-compose file (`pg_container`) as the host.
- **General:**
  - Name: test_database
- **Connection:**
  - Host name/address: pg_container
  - Username: root
  - Password: root
