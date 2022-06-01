---
permalink: /chords/a-minor/
common_script: chords_common.html
chord_factory: chord_factory.html
---
{% include_relative {{ page.common_script }} %}

# A Minor Chords
- [Am](#am)
- [Am7](#am7)

## Am

{% include_relative {{ page.chord_factory }}
   name="Am_chart"
   chord="
    {
       title: 'Am',
       fingers: [
         [1, 0],
         [2, 1, '1'],
         [3, 2, '3'],
         [4, 2, '2'],
         [5, 0],
         [6, 'x']
       ],
       barres: []
    }
   "
%}

## Am7

{% include_relative {{ page.chord_factory }}
   name="Am7_chart"
   chord="
    {
       title: 'Am7',
       fingers: [
         [1, 0],
         [2, 1, '1'],
         [3, 0],
         [4, 2, '2'],
         [5, 0],
         [6, 'x']
       ],
       barres: []
    }
   "
%}

