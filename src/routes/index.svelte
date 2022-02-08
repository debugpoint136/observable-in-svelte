<script>
  import { Runtime, Inspector } from '@observablehq/runtime';
  import notebook from '../c019e733534da627@316.js';

  // reference to mutable speed
  let speed = { value: 0.1 };

  function draw(node) {
    const runtime = new Runtime();
    runtime.module(notebook, Inspector.into(document.body));
  }
</script>

<p>
  Visit <a
    href="https://observablehq.com/@brunolaranjeira/d3-v6-force-directed-graph-with-directional-straight-arrow@316"
  >
    Observable</a
  > to read the documentation
</p>

<main>
  <div use:draw />
</main>
