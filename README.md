# Linea-del-tiempo
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Línea de Tiempo de la Evolución de la Robótica</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        .timeline {
            list-style: none;
            padding: 0;
            position: relative;
            margin: 50px 0;
        }
        .timeline-item {
            display: flex;
            width: 50%;
            margin: 0 auto;
            padding: 20px;
            background: #f1f1f1;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            position: relative;
        }
        .timeline-item::before {
            content: '';
            position: absolute;
            top: 15px;
            left: -6px;
            width: 12px;
            height: 12px;
            background: #007bff;
            border-radius: 50%;
            z-index: 1;
        }
        .timeline-item h2 {
            margin-top: 0;
            font-size: 1.2em;
        }
        .timeline-item p {
            font-size: 0.9em;
            color: #333;
        }
        .timeline-item.right {
            margin-left: auto;
            text-align: right;
        }
        .timeline-item.right::before {
            left: auto;
            right: -6px;
        }
    </style>
</head>
<body>
    <h1>Línea de Tiempo de la Evolución de la Robótica</h1>
    <ul class="timeline">
        <li class="timeline-item">
            <div>
                <h2>Antecedentes Históricos</h2>
                <p>Desde la antigua Grecia con los autómatas hasta la Revolución Industrial con los primeros autómatas industriales.</p>
            </div>
        </li>
        <li class="timeline-item right">
            <div>
                <h2>Siglo XX</h2>
                <p>Desarrollo de los primeros robots industriales programables y avances en la inteligencia artificial.</p>
            </div>
        </li>
        <li class="timeline-item">
            <div>
                <h2>Siglo XXI</h2>
                <p>Robótica móvil, avances en la interacción humano-robot y aplicaciones en diversos campos como la medicina y la exploración espacial.</p>
            </div>
        </li>
    </ul>
</body>
</html>
