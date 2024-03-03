# Patient-Management
Patient Database Management for Doctors, which includes appointment scheduling, patient history, emergency cases, patient's family history etc.



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Doctor Login</title>
    <!-- Your CSS styles here -->
</head>
<body>
    <div class="container">
        <h2>Doctor Login</h2>
        <form id="loginForm" onsubmit="return validateForm()">
            <label for="username">Username:</label>
            <input type="text" id="username" name="username" required>
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" required>
            <input type="submit" value="Login">
        </form>
    </div>
    <script>
        function validateForm() {
            // Dummy validation (replace with actual validation)
            var username = document.getElementById('username').value;
            var password = document.getElementById('password').value;
            if (username === 'doctor' && password === 'password') {
                window.location.href = 'dashboard.html';
                return false;
            } else {
                alert('Invalid username or password');
                return false;
            }
        }
    </script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Doctor Dashboard</title>
    <!-- Your CSS styles here -->
</head>
<body>
    <div class="container">
        <h2>Doctor Dashboard</h2>
        <ul>
            <li><a href="schedule.html">Appointment Scheduling</a></li>
            <li><a href="history.html">Patient History</a></li>
        </ul>
    </div>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Appointment Scheduling</title>
    <!-- Your CSS styles here -->
</head>
<body>
    <div class="container">
        <h2>Appointment Scheduling</h2>
        <!-- Your appointment scheduling form or content here -->
    </div>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Patient History</title>
    <!-- Your CSS styles here -->
</head>
<body>
    <div class="container">
        <h2>Patient History</h2>
        <!-- Your patient history display or content here -->
    </div>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Patient Database Management System</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Patient Database Management System</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#patients">Patients</a></li>
            <li><a href="#add-patient">Add Patient</a></li>
            <!-- Add more navigation links as needed -->
        </ul>
    </nav>
    <main>
        <section id="home">
            <h2>Welcome to the Patient Database Management System</h2>
            <!-- Add content for the home section -->
        </section>
        <section id="patients">
            <h2>Patients</h2>
            <table>
                <thead>
                    <tr>
                        <th>ID</th>
                        <th>Name</th>
                        <th>Age</th>
                        <!-- Add more table headers as needed -->
                    </tr>
                </thead>
                <tbody>
                    <!-- Rows for displaying patient data will be added dynamically -->
                </tbody>
            </table>
        </section>
        <section id="add-patient">
            <h2>Add Patient</h2>
            <form id="add-patient-form">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                <label for="age">Age:</label>
                <input type="number" id="age" name="age" required>
                <!-- Add more input fields for other patient details -->
                <button type="submit">Add Patient</button>
            </form>
        </section>
        <!-- Add more sections for different functionalities -->
    </main>
    <footer>
        <p>&copy; 2024 Patient Database Management System</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
    <title>Patient Management System</title>
</head>
<body>
    <h1>Patient Management System</h1>
    <table border="1">
        <tr>
            <th>First Name</th>
            <th>Last Name</th>
            <th>Date of Birth</th>
            <th>Address</th>
        </tr>
        <tr>
            <td>John</td>
            <td>Doe</td>
            <td>01-01-1980</td>
            <td>123 Main St</td>
        </tr>
        <tr>
            <td>Jane</td>
            <td>Smith</td>
            <td>02-02-1990</td>
            <td>456 Elm St</td>
        </tr>
        <!-- Add more rows for additional patients -->
    </table>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
    <title>Billing and Medicine Records</title>
</head>
<body>
    <h1>Billing and Medicine Records</h1>
    <h2>Patient 1</h2>
    <h3>Billing Information</h3>
    <ul>
        <li>Amount: $100.00</li>
        <li>Date: 01-01-2022</li>
    </ul>
    <h3>Medicine Records</h3>
    <ul>
        <li>Medicine: Medicine A</li>
        <li>Dosage: 1 pill per day</li>
    </ul>
    <h2>Patient 2</h2>
    <h3>Billing Information</h3>
    <ul>
        <li>Amount: $150.00</li>
        <li>Date: 02-01-2022</li>
    </ul>
    <h3>Medicine Records</h3>
    <ul>
        <li>Medicine: Medicine B</li>
        <li>Dosage: 2 pills per day</li>
    </ul>
    <!-- Add more patients and their billing/medicine records -->
</body>
</html>
