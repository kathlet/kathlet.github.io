---
title: "HTML Flight Data Viewer"
excerpt: "Short description of portfolio item number 1<br/><img src='/images/html_viewer.png'>"
collection: portfolio
---

Created a python tool that will take flight data for a specific datalog and output a html that allows easy analysis of the flight data with interactive plots. The attitude and flight path is updated live based on the cursor location. 

In this format, the flight data can be quickly looked at for initial analysis. The data is zoomed into the main flight window, determined by the initial increase in velocity from the flight data. 

An example of the HTML viewer is shown below, data is from a flight test on a Viper Scout. The buttons 'Toggle Map' and 'Attitude Indicator' toggle the visibility of an attitude indicator and a flight path which updates based on the cursor location on the flight data. Additionally, the sattelite count, framelosses, and RSSI is shown at the top of the document.

### Interactive Flight Data

<!-- <iframe src="/files/4-6-25_ViperScout_Flight2.html" width="100%" height="600" style="border:1px solid #ddd;">
  Your browser does not support iframes. Please view the data directly at
  <a href="/files/4-6-25_ViperScout_Flight2.html">ViperScout Flight 2 Data</a>.
</iframe> -->



<div class="full-bleed-iframe" style="position:relative;left:50%;right:50%;margin-left:-50vw;margin-right:-50vw;width:100vw;max-width:100vw;margin-top:3rem;">
  <iframe src="/files/4-6-25_ViperScout_Flight2.html" style="width:100%;height:700px;border:1px solid #ddd;" title="Flight data viewer" loading="lazy"></iframe>
</div>
