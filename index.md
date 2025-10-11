---
layout: default
title: My Portfolio
---

<!-- Link to your stylesheet -->
<link rel="stylesheet" type="text/css" href="Example3.css">

<!-- Vega + Vega-Lite + Vega-Embed scripts -->
<script src="https://cdn.jsdelivr.net/npm/vega@5"></script>
<script src="https://cdn.jsdelivr.net/npm/vega-lite@5"></script>
<script src="https://cdn.jsdelivr.net/npm/vega-embed@6"></script>

<style>
  #chartGrid {
    display: flex;
  }
</style>

<h1 class="big" style="margin-bottom: 0px;">
  Juan Xavier Gomez Illingworth
</h1>

<p style="margin-top: 0px; color: darkblue">
  <a href="JXGI CV 09-2025.pdf">CV</a> | <a href="https://www.linkedin.com/in/juan-xavier-gomez-illingworth">LinkedIn</a> | <a
            href="https://www.github.com/juanxgi83">GitHub</a>
</p>

<h3 class="small">
  This page acts as your portfolio of charts. You can use it as a good starting point to display your work but make sure to customise it to make it your own, or even start from scratch.
</h3>

<section>
  <div class="chart-description">
    <h2>Week 1: A basic chart</h2>
    <p>
      We've organised the page into sections, with each section containing a chart, title and a description.
      Here, we can describe the chart and give some context.
    </p>
  </div>
  <figure id="Location1"></figure>
</section>

<section>
  <div class="chart-description">
    <h2>Week 1: A basic chart</h2>
    <p>
      We've organised the page into sections, with each section containing a chart, title and a description.
      Here, we can describe the chart and give some context.
    </p>
  </div>
  <figure id="Location2"></figure>
</section>

<section>
  <div class="chart-description">
    <h2>Week 1: A basic chart</h2>
    <p>
      We've organised the page into sections, with each section containing a chart, title and a description.
      Here, we can describe the chart and give some context.
    </p>
  </div>
  <figure id="Location3"></figure>
</section>

<section>
  <div class="chart-description">
    <h2>Week 2: A Vega-Lite chart</h2>
    <p>
      We've organised the page into sections, with each section containing a chart, title and a description.
      Here, we can describe the chart and give some context.
    </p>
  </div>
  <figure id="Location4"></figure>
</section>

<section>
  <div class="chart-description">
    <h2>Week 2: A Vega-Lite chart</h2>
    <p>
      We've organised the page into sections, with each section containing a chart, title and a description.
      Here, we can describe the chart and give some context.
    </p>
  </div>
  <figure id="Location5"></figure>
</section>

<script>
  let figure_1_spec = "https://raw.githubusercontent.com/EconomicsObservatory/courses/main/2/s2_chart2.json"; 
  let figure_2_spec = "https://raw.githubusercontent.com/EconomicsObservatory/datavis/refs/heads/main/newsletters/2025-06-06-fixing-britain-how-can-left-behind-regions-catch-up/visualisation/fig2_local-authority-pay.json";
  let figure_3_spec = "fig1_reciprocal-tariffs.json";
  let figure_4_spec = "visualization.vl.json";
  let figure_5_spec = "visualization.vl (1).json";

  vegaEmbed('#Location1', figure_1_spec);
  vegaEmbed('#Location2', figure_2_spec);
  vegaEmbed('#Location3', figure_3_spec);
  vegaEmbed('#Location4', figure_4_spec);
  vegaEmbed('#Location5', figure_5_spec);
</script>



