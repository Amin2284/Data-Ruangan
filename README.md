# Data-Ruangan

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hospital Room and Medicine Prices</title>

    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
        }

        header {
            background-color: #cc0000;
            padding: 20px;
            color: white;
            text-align: center;
        }

        h1 {
            margin: 0;
            font-size: 36px;
        }

        h2 {
            color: #cc0000;
            font-size: 24px;
        }

        table {
            width: 80%;
            margin: 20px auto;
            border-collapse: collapse;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            background-color: white;
        }

        th, td {
            padding: 12px;
            text-align: left;
            border-bottom: 1px solid #ddd;
        }

        th {
            background-color: #cc0000;
            color: white;
        }

        tbody tr:hover {
            background-color: #f8f8f8;
        }

        img {
            width: 100%;
            height: auto;
            display: block;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>

<body>

    <header>
        <h1>Welcome to Our Hospital</h1>
    </header>

    <section>
        <h2>Room Prices</h2>
        <p>Below is a list of different room types available in our hospital, along with their respective prices per night.</p>
        <table>
            <thead>
                <tr>
                    <th>Room Type</th>
                    <th>Price</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Standard Room</td>
                    <td>$120 per night</td>
                </tr>
                <tr>
                    <td>Private Room</td>
                    <td>$200 per night</td>
                </tr>
                <tr>
                    <td>Intensive Care Unit (ICU)</td>
                    <td>$350 per night</td>
                </tr>
            </tbody>
        </table>
    </section>

    <section>
        <h2>Medicine Prices</h2>
        <p>Here is a list of commonly used medicines in our hospital, along with their respective prices. Please consult with our medical staff for prescriptions.</p>
        <table>
            <thead>
                <tr>
                    <th>Medicine</th>
                    <th>Price</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Painkillers</td>
                    <td>$8 per pack</td>
                </tr>
                <tr>
                    <td>Antibiotics</td>
                    <td>$12 per prescription</td>
                </tr>
                <tr>
                    <td>Anti-Inflammatory</td>
                    <td>$10 per pack</td>
                </tr>
                <tr>
                    <td>Antacid</td>
                    <td>$6 per pack</td>
                </tr>
                <tr>
                    <td>Cough Syrup</td>
                    <td>$9 per bottle</td>
                </tr>
                <tr>
                    <td>Allergy Medication</td>
                    <td>$15 per pack</td>
                </tr>
                <!-- Add more medicines as needed -->
            </tbody>
        </table>
    </section>

    <img src="https://source.unsplash.com/800x400/?hospital" alt="Hospital Image">

    <footer>
        &copy; 2023 Hospital Price List
    </footer>

</body>

</html>
