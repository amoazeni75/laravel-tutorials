<h1> Laravel Tutorials </h1>
<h3>To install Laravel locally</h3>
<ol>
  <li>Download and install the composer</li>
  <li>Create an empty folder to store your project inside it</li>
  <li>Open Command line inside the folder and paste these commands: <code>composer global require laravel/installer</code><span>   </span><code>composer create-project --prefer-dist laravel/laravel blog</code></li>
  <li>Download and install MySql depends on your OS (XAMPP is recommended for windows)</li>
  <li>Open ".env" file inside your project and change these parameters:</li>
  <ul>
    <li>Change APP_NAME to your project name, for example: "Basic Project"</li>
    <li>Change mail settings if you want to send email(you can create an account in "mailgun")</li>
    </li>Create a database and set its name, username, and password to the DB_DATABASE, DB_USERNAME, and DB_PASSWORD</li> 
  </ul>
</ol>
