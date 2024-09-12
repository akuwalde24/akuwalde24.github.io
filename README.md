# akuwalde24.github.io
<!-- index.html -->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LBus Management System</title>
    <style>
        /* Add some basic styling to make the page look decent */
        body {
            font-family: Arial, sans-serif;
        }
        .container {
            max-width: 800px;
            margin: 40px auto;
            padding: 20px;
            border: 1px solid #ddd;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>LBus Management System</h1>
        <form>
            <h2>Bus Details</h2>
            <label for="bus-number">Bus Number:</label>
            <input type="text" id="bus-number" name="bus-number"><br><br>
            <label for="route">Route:</label>
            <input type="text" id="route" name="route"><br><br>
            <label for="capacity">Capacity:</label>
            <input type="number" id="capacity" name="capacity"><br><br>
            <h2>Driver Details</h2>
            <label for="driver-name">Driver Name:</label>
            <input type="text" id="driver-name" name="driver-name"><br><br>
            <label for="driver-contact">Driver Contact:</label>
            <input type="tel" id="driver-contact" name="driver-contact"><br><br>
            <button type="submit">Add Bus</button>
        </form>
        <h2>Bus List</h2>
        <ul id="bus-list">
            <!-- This will be populated dynamically using JavaScript or a backend language -->
        </ul>
    </div>
    <script>
        // You can add JavaScript code here to handle form submissions, update the bus list, and perform other dynamic operations
    </script>
</body>
</html>
