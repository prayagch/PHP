# PHP
Here you can learn some code about php database connection
<?php
$servername = "localhost";
$username = "username";
$password = "password";

// Create connection
$conn = new mysqli($servername, $username, $password);

// Check connection
if ($conn->connect_error) {
    die("Connection failed: " . $conn->connect_error);
}
echo "Connected successfully";
?>
Visit my Wesite <a href="https://www.interviewqueries.com/">interview Queries</a>
