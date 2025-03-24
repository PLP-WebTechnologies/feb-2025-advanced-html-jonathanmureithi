<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Assignment</title>

</head>
<body>
    <h1>My HTML Assignment</h1>
    <ol type="I">
        <li>First item</li>
        <li>Second item</li>
        <li>Third item</li>
    </ol>
    
    <h2>Image from Pexels</h2>
    <img src="https://www.pexels.com/photo/a-car-on-a-road-22040027/" alt="a-car-on-a-road-22040027" width="300">

    <h2>Contacts Table</h2>
    <table border="1">
        <thead>
            <tr>
                <th>Name</th>
                <th>Address</th>
                <th>Mobile</th>
                <th>Email</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Alice Hunter</td>
                <td>Nairobi, Kenya</td>
                <td>+254712345678</td>
                <td>Alice.hunt@gmail.com</td>
            </tr>
            <tr>
                <td>Lewis Smith</td>
                <td>Kisumu, Kenya</td>
                <td>+254712345679</td>
                <td>lewissmith9@gmail.com</td>
            </tr>
        </tbody>
    </table>

    <h2>Registration Form</h2>
    <form action="#" method="post">
        
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" placeholder="Enter your name" required>
        <br><br>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" placeholder="Enter your email" required>
        <br><br>

        <label for="password">Password:</label>
        <input type="password" id="password" name="password" placeholder="Enter a password" required>
        <br><br>

        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" required>
        <br><br>

        <label for="gender">Gender:</label>
        <input type="radio" id="male" name="gender" value="Male" required>
        <label for="male">Male</label>
        <input type="radio" id="female" name="gender" value="Female" required>
        <label for="female">Female</label>
        <br><br>

        <label for="hobby">Hobbies:</label>
        <input type="checkbox" id="reading" name="hobby" value="Reading">
        <label for="reading">Reading</label>
        <input type="checkbox" id="sports" name="hobby" value="Sports">
        <label for="sports">Sports</label>
        <br><br>

        <label for="country">Country:</label>
        <select id="country" name="country" required>
            <option value="kenya">Kenya</option>
            <option value="uganda">Uganda</option>
            <option value="tanzania">Tanzania</option>
        </select>
        <br><br>

        <button type="submit">Register</button>
    </form>
    <h2>Multimedia</h2>
    <audio controls>
        <source src="audio-sample.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>
    <video controls width="400">
        <source src="video-sample.mp4" type="video/mp4">
        Your browser does not support the video element.
    </video>
</body>
</html>
