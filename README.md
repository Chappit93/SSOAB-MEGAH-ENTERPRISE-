# SSOAB-MEGAH-ENTERPRISE-

<!DOCTYPE html>
<html lang="ms">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SSOAB MEGAH ENTERPRISE - Laporan Projek</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #28a745;
            padding: 20px;
            text-align: center;
            color: white;
        }
        h1 {
            margin: 0;
        }
        .form-container {
            width: 80%;
            margin: 20px auto;
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        label {
            font-weight: bold;
        }
        input, textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border-radius: 4px;
            border: 1px solid #ddd;
        }
        button {
            background-color: #28a745;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        button:hover {
            background-color: #218838;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #28a745;
            color: white;
        }
    </style>
</head>
<body>

<header>
    <h1>SSOAB MEGAH ENTERPRISE</h1>
    <p>Laporan Projek - Supervisor</p>
</header>

<div class="form-container">
    <h2>Isi Laporan Projek</h2>
    <form action="/submit_laporan" method="POST">
        <label for="projek">Nama Projek:</label>
        <input type="text" id="projek" name="projek" required>

        <label for="tarikh">Tarikh:</label>
        <input type="date" id="tarikh" name="tarikh" required>

        <label for="status">Status Projek:</label>
        <textarea id="status" name="status" rows="4" required></textarea>

        <label for="catatan">Catatan:</label>
        <textarea id="catatan" name="catatan" rows="4"></textarea>

        <button type="submit">Hantar Laporan</button>
    </form>
</div>

<footer>
    <p>SSOAB MEGAH ENTERPRISE - Semua Hak Cipta Terpelihara</p>
</footer>

</body>
</html>
