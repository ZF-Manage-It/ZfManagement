ZfManagement
============
  - Uses ZendAuth and ZendRbac to control access the management dashboard
  - Affects nothing on the frontend of the application
  - Triggers events for successful login, logout
  - Triggers an event when preparing to load the management dashboard
  - Dashboard is capable of loading other modules following a predefined interface
  - Only performs CRUD actions for Management Users out of the box
  - Contains a php setup script for creating the database schema