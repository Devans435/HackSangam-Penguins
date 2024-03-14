# HackSangam-Penguins
<!DOCTYPE html>
<html>
<head>
    <title>Penguins Waste Management</title>
    <style>
      
      body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            color: #333;
            margin: 0;
            padding: 0;
            background-color: white;
        }

        header {
            background-color: #4CAF50;
            padding: 1rem;
        }

        header h1 {
            color: white;
            text-align: center;
            margin: 0;
        }

        nav {
            background-color: #343a40;
            padding: 1rem;
            text-align: center;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
        }

        nav ul li {
            display: inline;
            margin: 0 1rem;
        }

        nav ul li a {
            text-decoration: none;
            color: #fff;
            font-size: 18px;
            transition: color 0.3s;
        }

        nav ul li a:hover {
            color: #41ff07;
        }

        main {
            padding: 2rem;
        }

        main section {
            margin-bottom: 2rem;
        }

        footer {
            background-color: #343a40;
            color: white;
            text-align: center;
            padding: 1rem;
        }

        h2 {
            color: #343a40;
            text-align: center;
            margin-bottom: 1.5rem;
            font-size: 24px;
        }

        p {
            margin-bottom: 1rem;
            font-size: 18px;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 1.5rem;
            border-radius: 10px;
            overflow: hidden;
        }

        th, td {
            border: 1px solid #ccc;
            padding: 12px 15px;
            text-align: left;
        }

        th {
            background-color: #4CAF50;
            color: white;
            font-size: 18px;
            text-transform: uppercase;
        }

        tbody tr:nth-child(even) {
            background-color: #f2f2f2;
        }

        form {
            max-width: 500px;
            margin: auto;
            background-color: #f9f9f9;
            padding: 70px;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        label {
            font-weight: bold;
            display: block;
            margin-bottom: 10px;
            font-size: 18px;
        }

        input[type="text"],
        input[type="email"],
        textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 20px;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 16px;
        }

        input[type="submit"] {
            background-color: #4CAF50;
            color: white;
            padding: 12px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 18px;
            transition: background-color 0.3s;
        }

        input[type="submit"]:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <header>
        <h1>Smart Waste Management</h1>
    </header>

    <nav>
        <ul>
            <li><a href="#" onclick="showSection('home')">Home</a></li>
            <li><a href="#" onclick="showSection('areas')">Areas</a></li>
            <li><a href="#" onclick="showSection('alerts')">Alerts</a></li>
            <li><a href="#" onclick="showSection('complaints')">Complaints</a></li>
            <li><a href="#" onclick="showSection('about')">About us</a></li>
        </ul>
    </nav>

    <main>
        <section id="home">
            <center>
                <h2>Welcome to Smart Waste Management</h2>
                <p>Your trusted partner for waste management services.</p>
            </center> 
            <img src="image14.png" alt="loading image" style="width: 80%; height: auto; margin-left: 8rem; border: 2px solid #333;">
        </section>

        <section id="areas" style="display: none;">
            <h2>Areas We Serve</h2>
            <table>
                <thead>
                    <tr>
                        <th>S. no.</th>
                        <th>Area/Sector</th>
                        <th>Report</th>
                        <th>History</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>1.</td>
                        <td>XYZ Area</td>
                        <td><button style="width: 200px; height: 50px; border-radius: 1rem; font-size: 18px; background-color: #343a40; color: #ccc;"><a href="report.html" style="color: white; text-decoration: none;" target="_blank">See Report</a></button></td>
                        <td><button style="width: 200px; height: 50px; border-radius: 1rem; font-size: 18px; background-color: #343a40; color: #ccc;"><a href="waste_management_history.html" style="color: white; text-decoration: none;" target="_blank">See History</a></button></td>
                    </tr>
                    <tr>
                        <td>2.</td>
                        <td>Sector 9</td>
                        <td><button style="width: 200px; height: 50px; border-radius: 1rem; font-size: 18px; background-color: #343a40; color: #ccc;"><a href="#" style="color: white; text-decoration: none;" target="_blank">See Report</a></button></td>
                        <td><button style="width: 200px; height: 50px; border-radius: 1rem; font-size: 18px; background-color: #343a40; color: #ccc;"><a href="#" style="color: white; text-decoration: none;" target="_blank">See History</a></button></td>
                    </tr>
                    <tr>
                        <td>3.</td>
                        <td>XYZ Square</td>
                        <td><button style="width: 200px; height: 50px; border-radius: 1rem; font-size: 18px; background-color: #343a40; color: #ccc;"><a href="#" style="color: white; text-decoration: none;" target="_blank">See Report</a></button></td>
                        <td><button style="width: 200px; height: 50px; border-radius: 1rem; font-size: 18px; background-color: #343a40; color: #ccc;"><a href="#" style="color: white; text-decoration: none;" target="_blank">See History</a></button></td>
                    </tr>
                    <tr>
                        <td>4.</td>
                        <td>XYZ Square</td>
                        <td><button style="width: 200px; height: 50px; border-radius: 1rem; font-size: 18px; background-color: #343a40; color: #ccc;"><a href="#" style="color: white; text-decoration: none;" target="_blank">See Report</a></button></td>
                        <td><button style="width: 200px; height: 50px; border-radius: 1rem; font-size: 18px; background-color: #343a40; color: #ccc;"><a href="#" style="color: white; text-decoration: none;" target="_blank">See History</a></button></td>
                    </tr>
                    <tr>
                        <td>5.</td>
                        <td>XYZ Square</td>
                        <td><button style="width: 200px; height: 50px; border-radius: 1rem; font-size: 18px; background-color: #343a40; color: #ccc;"><a href="#" style="color: white; text-decoration: none;" target="_blank">See Report</a></button></td>
                        <td><button style="width: 200px; height: 50px; border-radius: 1rem; font-size: 18px; background-color: #343a40; color: #ccc;"><a href="#" style="color: white; text-decoration: none;" target="_blank">See History</a></button></td>
                    </tr>
                    <tr>
                        <td>6.</td>
                        <td>XYZ Square</td>
                        <td><button style="width: 200px; height: 50px; border-radius: 1rem; font-size: 18px; background-color: #343a40; color: #ccc;"><a href="#" style="color: white; text-decoration: none;" target="_blank">See Report</a></button></td>
                        <td><button style="width: 200px; height: 50px; border-radius: 1rem; font-size: 18px; background-color: #343a40; color: #ccc;"><a href="#" style="color: white; text-decoration: none;" target="_blank">See History</a></button></td>
                    </tr>
                    <tr>
                        <td>7.</td>
                        <td>XYZ Square</td>
                        <td><button style="width: 200px; height: 50px; border-radius: 1rem; font-size: 18px; background-color: #343a40; color: #ccc;"><a href="#" style="color: white; text-decoration: none;" target="_blank">See Report</a></button></td>
                        <td><button style="width: 200px; height: 50px; border-radius: 1rem; font-size: 18px; background-color: #343a40; color: #ccc;"><a href="#" style="color: white; text-decoration: none;" target="_blank">See History</a></button></td>
                    </tr>
                </tbody>
            </table>
        </section>

        <section id="alerts" style="display: none;">
            <h2 style="color: #343a40;">Alerts</h2>
            <table>
                <thead>
                    <tr>
                        <th>Location</th>
                        <th>Number of Alerts</th>
                        <th>Last Filled</th>
                    </tr>
                </thead>
                <tbody id="dustbinTableBody">
                    <!-- Data will be inserted here -->
                </tbody>
            </table>
        </section>

        <section id="complaints" style="display: none;">
            <h2>Complaints</h2>
            <p>If you have any complaints or issues regarding our waste management services, please let us know by clicking the "Write a complaint" button below. You can also take a photo of the issue and attach it to your complaint.</p>
            <center>
                <button id="takePhotoButton" style="width: 200px; height: 50px; border-radius: 1rem; font-size: 18px; background-color: #343a40; color: #ccc;">Take a photo</button>
                <button id="writeComplaintButton" style="width: 200px; height:50px; border-radius: 1rem; font-size: 18px; background-color: #343a40; color: #ccc;" >Write a complaint</button>
            </center>
            
            <form id="complaintForm" style="display: none;">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required><br><br>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required><br><br>

                <label for="complaint">Complaint:</label><br>
                <textarea id="complaint" name="complaint" rows="4" cols="50" required></textarea><br><br>

                <label for="photo">Photo:</label><br>
                <input type="file" id="photo" name="photo"><br><br>

                <input type="submit" value="Submit complaint">
            </form>
        </section>

        <section id="about" style="display: none;">
            <h2><u>Contact us</u></h2>
            <p><u>Feedback:</u></p>
            <form action="submit_feedback.php" method="post">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required><br><br>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required><br><br>

                <label for="feedback">Feedback:</label><br>
                <textarea id="feedback" name="feedback" rows="4" cols="50" required></textarea><br><br>

                <input type="submit" value="Submit feedback">
            </form>
        </section>
    </main>

    <script>
        const dustbinData = [
            { areaName: 'XYZ', alerts: 10, timeFilled: '12:00 PM' },
            { areaName: 'sector 24', alerts: 5, timeFilled: '2:30 PM' },
            { areaName: 'sector 9 ', alerts: 8, timeFilled: '10:00 AM' },
            { areaName: 'sector 4', alerts: 12, timeFilled: '8:00 AM' },
            { areaName: 'sector 31', alerts: 2, timeFilled: '3:00 PM' },
            { areaName: 'sector 4', alerts: 7, timeFilled: '11:45 AM' },
            { areaName: 'sector', alerts: 15, timeFilled: '9:30 AM' },
        ];

        const dustbinTableBody = document.getElementById('dustbinTableBody');

        dustbinData.forEach(data => {
            const row = document.createElement('tr');
            const locationCell = document.createElement('td');
            const alertsCell = document.createElement('td');
            const timeFilledCell = document.createElement('td');

            const graphic = document.createElement('div');
            graphic.className = 'graphic';

            const areaLink = document.createElement('a');
            areaLink.href = '#'; // Add your link here
            areaLink.target = '_blank'; // Open in a new tab
            areaLink.textContent = data.areaName;

            locationCell.appendChild(graphic);
            locationCell.appendChild(areaLink); // Append the link instead of textContent
            alertsCell.textContent = data.alerts;
            timeFilledCell.textContent = data.timeFilled;

            row.appendChild(locationCell);
            row.appendChild(alertsCell);
            row.appendChild(timeFilledCell);

            dustbinTableBody.appendChild(row);
        });

        document.getElementById('takePhotoButton').addEventListener('click', function() {
          // Open the camera app or photo library to take a photo
          // You can use a library like Camera API or cordova-plugin-camera to do this
          // Once the photo is taken, set the value of the "photo" input to the photo file
          var photoInput = document.getElementById('photo');
          photoInput.click();
        });

        document.getElementById('writeComplaintButton').addEventListener('click', function() {
          // Show the complaint form
          var complaintForm = document.getElementById('complaintForm');
          complaintForm.style.display = 'block';
        });

        document.getElementById('complaintForm').addEventListener('submit', function(event) {
          // Prevent the form from submitting normally
          event.preventDefault();

          // Get the form data
          var formData = new FormData(event.target);

          // Send the form data to the server using AJAX or Fetch API
          // You can use a library like Axios or jQuery to simplify the AJAX request
          // Once the server responds, you can show a success or error message
        });

        function showSection(sectionId) {
            var sections = document.querySelectorAll('section');
            for (var i = 0; i < sections.length; i++) {
                if (sections[i].id === sectionId) {
                    sections[i].style.display = 'block';
                } else {
                    sections[i].style.display = 'none';
                }
            }
        }
    </script>
</body>
</html>
