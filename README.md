<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CRUD de Problemas de PC</title>
</head>
<body>
    <h1>CRUD de Problemas de PC</h1>

    <label for="numeroPC">Número de PC:</label>
    <input type="text" id="numeroPC">
    
    <label for="problemaPC">Problema de PC:</label>
    <input type="text" id="problemaPC">
    
    <button onclick="agregarProblema()">Agregar Problema</button>

    <h2>Lista de Problemas</h2>
    <table border="1">
        <thead>
            <tr>
                <th>Índice</th>
                <th>Número de PC</th>
                <th>Problema</th>
            </tr>
        </thead>
        <tbody id="tablaProblemas">
            <!-- Aquí se mostrarán los problemas -->
        </tbody>
    </table>

    <script src="./JS/app.js"></script>
       
    
</body>
</html>

