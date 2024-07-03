<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: 20px auto;
            overflow: hidden;
        }
        .profile-img {
            float: left;
            width: 200px;
            height: 200px;
            margin-right: 20px;
            border-radius: 50%;
            object-fit: cover;
        }
        .bio {
            overflow: hidden;
        }
        .bio h2 {
            margin-top: 0;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Portfolio</h1>
    </header>
    <div class="container">
        <div class="bio">
            <img src="your-photo.jpg" alt="Your Photo" class="profile-img">
            <h2>Your Name</h2>
            <p>Hello! I am a student preparing for the JEE. I have a passion for [Your Interests]. Currently, I am focusing on [Your Focus Areas]. I love to learn new things and take on challenges. My goal is to [Your Goals].</p>
        </div>
    </div>
    <footer>
        <p>Contact me at <a href="mailto:your-email@example.com" style="color: white;">your-email@example.com</a></p>
    </footer>
</body>
</html>
