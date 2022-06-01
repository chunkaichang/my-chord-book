---
permalink: /chords/f-major/
common_script: chords_common.html
chord_factory: chord_factory.html
---
{% include_relative {{ page.common_script }} %}

# F Major Chords
- [F](#f)
- [Fmaj7](#fmaj7)

## F

{% include_relative {{ page.chord_factory }}
   name="F_chart"
   chord="
    {
       title: 'F',
       fingers: [
         [3, 2, '2'],
         [4, 3, '4'],
         [5, 3, '3']
       ],
       barres: [
         {
           fromString: 6,
           toString: 1,
           fret: 1
         }
       ]
    }
   "
%}

## Fmaj7

{% include_relative {{ page.chord_factory }}
   name="Fmaj7_chart"
   chord="
    {
       title: 'Fmaj7',
       fingers: [
         [1, 0],
         [2, 1, '1'],
         [3, 2, '2'],
         [4, 3, '3'],
         [5, 'x'],
         [6, 'x']
       ],
       barres: []
    }
   "
%}

