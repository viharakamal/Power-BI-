<h1 align="center">📊 Power BI Visualization Guide</h1>
<p align="center"><b>Maps | Filled Maps | Cards | Bar Charts</b></p>

<hr>

<h2>🗺️ 1. Map Visual (Normal Map)</h2>

<p><b>What is a Map Visual?</b><br>
A Map visual displays geographical data using bubble points plotted on a world map. It is used to compare values across locations.</p>

<img src="https://miro.medium.com/v2/resize:fit:1400/1*51unQm1-UO8V9PygR4ZZ3A.png" width="600">

<h3>Key Fields</h3>
<ul>
  <li><b>Location</b> – Country, State, City, Postal Code</li>
  <li><b>Latitude & Longitude</b> – Improves accuracy</li>
  <li><b>Size</b> – Determines bubble size (e.g., Sales)</li>
  <li><b>Color Saturation</b> – Adds color intensity based on value</li>
</ul>

<hr>

<h2>🗺️ 2. Filled Map (Choropleth Map)</h2>

<p><b>What is a Filled Map?</b><br>
A Filled Map shades entire regions based on values. It is used to show intensity across areas (heatmap style).</p>

<img src="https://learn.microsoft.com/en-us/power-bi/visuals/media/power-bi-visualization-filled-map/power-bi-filled-map.png" width="600">

<h3>Use Cases</h3>
<ul>
  <li>Revenue by State</li>
  <li>Population Density</li>
  <li>Region-wise Performance</li>
</ul>

<hr>

<h2>🃏 3. Card Visual</h2>

<p><b>What is a Card?</b><br>
A Card visual displays a single KPI metric clearly and prominently on dashboards.</p>

<img src="https://learn.microsoft.com/en-us/power-bi/create-reports/media/power-bi-report-add-visualizations/power-bi-visual-card.png" width="400">

<h3>Use Cases</h3>
<ul>
  <li>Total Sales</li>
  <li>Total Customers</li>
  <li>Total Profit</li>
  <li>Year-to-Date Values</li>
</ul>

<hr>

<h2>📊 4. Bar Charts in Power BI</h2>

<p>Bar charts are used to compare categories using horizontal or vertical bars. Power BI provides multiple types of bar/column charts.</p>

<!-- Clustered Bar Chart -->
<h3>📘 4.1 Clustered Bar Chart</h3>
<img src="https://learn.microsoft.com/en-us/power-bi/visuals/media/power-bi-visualization-bar-and-column-charts/power-bi-clustered-bar-chart.png" width="600">
<p>Compares multiple categories side-by-side.</p>

<!-- Stacked Bar Chart -->
<h3>📙 4.2 Stacked Bar Chart</h3>
<img src="https://learn.microsoft.com/en-us/power-bi/visuals/media/power-bi-visualization-bar-and-column-charts/power-bi-stacked-bar-chart.png" width="600">
<p>Shows how different subcategories contribute to a total.</p>

<!-- 100% Stacked Bar Chart -->
<h3>📗 4.3 100% Stacked Bar Chart</h3>
<img src="https://learn.microsoft.com/en-us/power-bi/visuals/media/power-bi-visualization-bar-and-column-charts/power-bi-100-stacked-bar-chart.png" width="600">
<p>Shows contribution in percentage form.</p>

<!-- Clustered Column Chart -->
<h3>📕 4.4 Clustered Column Chart</h3>
<img src="https://learn.microsoft.com/en-us/power-bi/visuals/media/power-bi-visualization-bar-and-column-charts/power-bi-clustered-column-chart.png" width="600">

<!-- Stacked Column Chart -->
<h3>📒 4.5 Stacked Column Chart</h3>
<img src="https://learn.microsoft.com/en-us/power-bi/visuals/media/power-bi-visualization-bar-and-column-charts/power-bi-stacked-column-chart.png" width="600">

<!-- 100% Stacked Column Chart -->
<h3>📓 4.6 100% Stacked Column Chart</h3>
<img src="https://learn.microsoft.com/en-us/power-bi/visuals/media/power-bi-visualization-bar-and-column-charts/power-bi-100-stacked-column-chart.png" width="600">

<hr>

<h2>📌 Summary</h2>

<table>
  <tr>
    <th>Visual</th>
    <th>Best For</th>
    <th>Example</th>
  </tr>
  <tr>
    <td>Map</td>
    <td>City-level comparison</td>
    <td>Sales by Store</td>
  </tr>
  <tr>
    <td>Filled Map</td>
    <td>Region shading</td>
    <td>Revenue by State</td>
  </tr>
  <tr>
    <td>Card</td>
    <td>KPI numbers</td>
    <td>Total Sales</td>
  </tr>
  <tr>
    <td>Clustered Bar/Column</td>
    <td>Compare categories</td>
    <td>Sales by Region</td>
  </tr>
  <tr>
    <td>Stacked Bar/Column</td>
    <td>Show part-to-whole</td>
    <td>Revenue Breakdown</td>
  </tr>
  <tr>
    <td>100% Stacked Charts</td>
    <td>Percentage comparison</td>
    <td>Category Contribution</td>
  </tr>
</table>
