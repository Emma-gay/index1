<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title> Aprendizaje html </title>
 <html>
<head>
    <meta charset="UTF-8">
    <title>Ejemplo de Tabla</title>
    <style>
        table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 8px;
            text-align: left;
        }
        th {
            background-color: #f2f2f2;
        }
    </style>
</head>
<body>
    <h1>Tabla de Ejemplo</h1>
    <table>
        <thead>
            <tr>
                <th>Nombre</th>
                <th>Edad</th>
                <th>Ciudad</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Juan</td>
                <td>30</td>
                <td>Madrid</td>
            </tr>
            <tr>
                <td>Maria</td>
                <td>25</td>
                <td>Barcelona</td>
            </tr>
            <tr>
                <td>Pedro</td>
                <td>35</td>
                <td>Valencia</td>
            </tr>
        </tbody>
        <tfoot>
            <tr>
                <td colspan="3">Datos de ejemplo</td>
            </tr>
        </tfoot>
    </table>
</body>
</html>
