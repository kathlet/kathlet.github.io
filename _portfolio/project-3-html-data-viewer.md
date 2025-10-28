---
title: "HTML Flight Data Viewer"
excerpt: "Developed a Python tool to automatically parse flight datalogs and generate a self-contained, interactive HTML dashboard. Features include cursor-linked plots, a live attitude indicator, and a flight path map for rapid analysis.<br/><img src='/images/html_viewer.png'>"
collection: portfolio
---

### Problem & Solution

Raw flight datalogs are dense and difficult to analyze quickly. To streamline this process, I developed a Python tool that automatically parses a flight datalog and generates a single, self-contained HTML file.

This file provides an interactive dashboard, allowing pilots and engineers to easily review flight data. The data is automatically zoomed to the main "flight window" (determined by the initial increase in velocity), filtering out ground setup and post-flight noise.

### Key Features

* **Interactive Data Plots:** All flight data is presented in interactive plots. Hovering the cursor at any point in time updates all other widgets on the page.
* **Live-Updating Widgets:** The dashboard includes:
    * An **Attitude Indicator** that updates based on the cursor's time position.
    * A **2D Flight Path Map** that plots the aircraft's position, also linked to the cursor.
    * Both widgets can be toggled on or off by the user.
* **Heads-Up Display (HUD):** Critical data such as satellite count, framelosses, and RSSI are displayed at the top for a constant, easy-to-read overview.

### Interactive Demo

Below is an embedded example from a flight test on a Viper Scout. Hover your mouse over the plots to see the attitude indicator and map update in real-time.

<!-- <iframe src="/files/4-6-25_ViperScout_Flight2.html" width="100%" height="600" style="border:1px solid #ddd;">
  Your browser does not support iframes. Please view the data directly at
  <a href="/files/4-6-25_ViperScout_Flight2.html">ViperScout Flight 2 Data</a>.
</iframe> -->



<div class="full-bleed-iframe" style="position:relative;left:50%;right:50%;margin-left:-50vw;margin-right:-50vw;width:100vw;max-width:100vw;margin-top:3rem;">
  <iframe src="/files/4-6-25_ViperScout_Flight2.html" style="width:100%;height:700px;border:1px solid #ddd;" title="Flight data viewer" loading="lazy"></iframe>
</div>
