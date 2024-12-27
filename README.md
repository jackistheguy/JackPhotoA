# JackPhotoA
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        main {
            padding: 20px;
            text-align: center;
        }
        footer {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        .upload-form {
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Website</h1>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>
    <main>
        <h2>Hello, World!</h2>
        <p>This is a basic example of a website created with HTML and CSS.</p>
        <p>You can add more content and style it as needed!</p>

        <!-- File Upload Form -->
        <div class="upload-form">
            <form action="/upload" method="post" enctype="multipart/form-data">
                <label for="file">Upload your photo:</label>
                <input type="file" id="file" name="file" accept="image/*">
                <button type="submit">Submit</button>
            </form>
        </div>
    </main>
    <footer>
        <p>© 2024 My Website. All rights reserved.</p>
    </footer>
</body>
</html>
