# random
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Report</title>
    <style>
    :root {
      --bg-color: #f5f7fa;
      --text-color: #2c3e50;
      --chart-bg: #ffffff;
      --tab-bg: #e0e0e0;
      --tab-hover: #cccccc;
      --tab-active: #3594f9;
    }

    body {
      font-family: Arial, sans-serif;
      margin: 20px;
      background-color: var(--bg-color);
      color: var(--text-color);
    }

    h1 {
      text-align: center;
      margin-bottom: 20px;
      color: var(--text-color);
    }

    #tabs {
      text-align: center;
      margin-bottom: 20px;
    }

    .tab {
      display: inline-block;
      margin-right: 10px;
      padding: 10px 20px;
      border-radius: 5px;
      cursor: pointer;
      font-weight: bold;
      background-color: var(--tab-bg);
      transition: background-color 0.3s;
      color: var(--text-color);
    }

    .tab:hover {
      background-color: var(--tab-hover);
    }

    .active-tab {
      background-color: var(--tab-active);
      color: #fff;
    }

    .tab-content {
      display: none;
    }

    .active-tab-content {
      display: block;
    }

    .chart-container {
      margin-bottom: 20px;
    }

    .chart-container canvas {
      width: 100%;
      height: auto;
      border-radius: 8px;
      background-color: var(--chart-bg);
    }

    .chart-row {
      display: flex;
      justify-content: space-evenly;
      margin-bottom: 20px;
      gap: 20px;
    }

    .chart-row > div {
      width: 45%;
      box-sizing: border-box;
    }

    .chart-container h3 {
      text-align: center;
      margin-bottom: 10px;
      color: var(--text-color);
    }
  </style>

    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <script>
        // Global configuration to disable animations
        Chart.defaults.animation = false;
    </script>
</head>
