---
title: "C Major Chords"
permalink: /my-chord-book/c-major/
---
# C Major Chords

## C
<!--container of the chart-->
<div id="chart"></div>

<!--load umd script -->
<script src="https://omnibrain.github.io/svguitar/js/svguitar.umd.js"></script>

<script>
  // initialize the chart
  var chart = new svguitar.SVGuitarChord('#chart')

  // draw the chart
  chart
    .chord({
      title: 'C',
      fingers: [
        [1, 0],
        [2, 1, '1'],
        [3, 0],
        [4, 2, '2'],
        [5, 3, '3'],
        [6, 'x']
      ]
    })
    .configure({
      orientation: 'horizontal',
    })
    .draw()
</script>
