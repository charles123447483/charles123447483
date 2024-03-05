<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>3D Print Generator</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
        }
        .container {
            margin-top: 100px;
        }
        button {
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            background-color: #007bff;
            color: #fff;
            border: none;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>3D Print Generator</h1>
        <p>Click the button below to generate your 3D print STL file.</p>
        <button onclick="generateSTL()">Generate STL</button>
        <div id="message"></div>
    </div>

    <script>
        function generateSTL() {
            // Placeholder function to simulate generating STL file
            // In a real application, this function would trigger the process to generate the STL file
            // and provide a link to download it
            document.getElementById('message').innerHTML = "<p>STL file generation initiated...</p>";
            setTimeout(function() {
                document.getElementById('message').innerHTML = "<p>STL file generated successfully! <a href='#'>Download STL</a></p>";
            }, 2000); // Simulating a delay for demonstration purposes
        }
    </script>
</body>
</html>
