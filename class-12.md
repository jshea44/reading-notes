# Readings: Chart.js, Canvas
This reading was focused a bit more on the visual side of things from creating 2D images to applying charts. The charts themselves can be useful if you are trying to display data in a visual format.
## JavaScript Canvas
  1. The element `canvas` allows 2D graphics to be drawn using javascript.
  2. The closing tag is important because anything that is between the tags is fallback content if the browser doesn't support `canvas`.
  3. The `getContext()` method returns a render context object. You pass in '2d' to get a 2D rendering context object.

## Chart.js Documentation:
  1. Chart.js is an open-sourced charting library and provides a set of frequently used chart types, plugins, and customization options. First you have to install it, then it can be used by the following script tag:
  <script src="path/to/chartjs/dist/chart.umd.js"></script>
<script>
    const myChart = new Chart(ctx, {...});
</script>
  3. Three different chart types are: Area Chart, Line Chart, and Radar Chart.

## Easily Create Stunning Animated Charts with Chart.js
  1. One of the biggest benefits is that they’re easier to look at and convey data quickly.
  2. Charts could have helped visually when dealing with the salmon cookies project. Having the data in tables is nice for viewing all the information, but have the additional chart would be nice if you just wanted something that display the information quickly and effectively without having to get into every data piece.

## Things I want to learn more about
