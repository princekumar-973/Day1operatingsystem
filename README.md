# Day1operatingsystem

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Garbage Collection Simulation</title>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <link rel="stylesheet" href="osfinal.css"> <!-- Updated from styles.css -->
</head>
<body>
    <div class="container">
        <h1>Garbage Collection <span>Visualizer</span></h1>
        <div class="charts-container">
            <div class="chart-container">
                <h3>Memory Usage Over Time</h3>
                <canvas id="memoryChart"></canvas>
            </div>
            <div class="chart-container">
                <h3>Resource Allocation</h3>
                <canvas id="allocationChart"></canvas>
            </div>
        </div>
        <div>
            <div class="controls">
                <button id="resetBtn" class="btn reset">Reset</button>
                <button id="allocateBtn" class="btn allocate">Allocate</button>
                <button id="collectBtn" class="btn collect">Collect</button>
            </div>
            <div class="memory-usage">
                <h3>Memory Usage</h3>
                <div class="progress-bar">
                    <div id="progress" class="progress"></div>
                </div>
                <span id="usage">139 / 300 MB</span>
            </div>
