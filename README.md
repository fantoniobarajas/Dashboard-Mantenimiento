<!DOCTYPE html>
<html lang="es">

<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Dashboard BBVA</title>

<link rel="stylesheet" href="style.css">

<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>

</head>

<body>

<header>

    <div class="logo">
        Dashboard Corporativo BBVA
    </div>

    <div id="fecha"></div>

</header>

<main>

    <section class="kpis">

        <div class="card">
            <h3>Visitas Integrales</h3>
            <p id="visitas">0%</p>
        </div>

        <div class="card">
            <h3>Tickets Correctivos</h3>
            <p id="correctivos">0</p>
        </div>

        <div class="card">
            <h3>Indisponibilidad</h3>
            <p id="indisponibilidad">0%</p>
        </div>

    </section>

    <section class="charts">

        <div class="chart-card">
            <canvas id="chartSupervisores"></canvas>
        </div>

    </section>

    <section class="tabla">

        <table>

            <thead>
                <tr>
                    <th>Supervisor</th>
                    <th>Empresa</th>
                    <th>DZ</th>
                    <th>Cumplimiento</th>
                </tr>
            </thead>

            <tbody id="tablaBody"></tbody>

        </table>

    </section>

</main>

<script src="app.js"></script>

</body>
</html>
