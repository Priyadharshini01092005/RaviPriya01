<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Salary Details</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }

        #salary-details {
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 20px;
        }

        table {
            border-collapse: collapse;
            width: 50%;
        }

        th, td {
            border: 1px solid #ddd;
            padding: 10px;
            text-align: left;
        }

        th {
            background-color: #333;
            color: #fff;
        }
    </style>
</head>
<body>
    <header>
        <h1>Salary Details</h1>
    </header>
    <main>
        <div id="salary-details">
            <h2>Employee Salary Details</h2>
            <table id="salary-table">
                <tr>
                    <th>Employee ID</th>
                    <th>Employee Name</th>
                    <th>Basic Salary</th>
                    <th>HRA</th>
                    <th>TA</th>
                    <th>Total Salary</th>
                </tr>
                <!-- Table rows will be generated dynamically -->
            </table>
        </div>
    </main>
</body>
</html>
