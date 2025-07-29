# Private-Network-Setup-UDC-Server

## Web Server (`udc.example.com`)
1. Install Apache and PHP.
2. Start and verify PHP with a test page.
3. Ensure the page loads in the browser (adjust firewall if needed).

## Database Server (`dbsvr.example.com`)
1. Clone and rename the web server.
2. Disable firewall and remove bridged networking.
3. Install MySQL with UTF-8 settings.
4. Secure MySQL and create a test database.

## UDC Application Configuration
1. Create `udc` database and grant user privileges.
2. Verify remote access from web server.
3. Create `users` table to store form data.
4. Configure upload directories with appropriate permissions.

## Application Workflow
1. PHP page connects to MySQL and confirms connectivity.
2. Main app collects user info and files.
3. Data is stored in the DB; files saved locally.
