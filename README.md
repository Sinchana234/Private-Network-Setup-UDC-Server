Web Server (udc.example.com)

1.Install Apache and PHP
2.Verify PHP and start the web service
3.Create a test PHP page to confirm setup
4.Access the page via browser; adjust firewall if needed

Database Server (dbsvr.example.com)

1.Clone the web server and assign a new hostname
2.Disable firewall and remove bridged network
3.Install and configure MySQL with UTF-8 support
4.Secure MySQL and create a test database

UDC Application Configuration

1.Create udc database and user with full access
2.Verify remote connection from web server
3.Create users table for storing form data
4.Set up upload directories with proper permissions

Application Functionality

1.PHP page connects to database and verifies connectivity
2.Main application page collects user data and uploads files
3.Submitted data is stored in the database and files saved locally
