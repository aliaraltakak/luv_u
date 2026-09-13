# Özge 🩵

A beating heart for a long-distance relationship, as a single static page.

- The heart is the Taubin surface `(x² + 9/4·y² + z² − 1)³ − x²z³ − 9/80·y²z³ = 0`, raymarched in a WebGL fragment shader.
- The beat is a two-spike "lub-dub" pulse `s(t)` that scales the surface at 72 bpm.
- The countdown runs to a fixed UTC instant so it reads the same in both time zones, and shows the number of heartbeats left until then.

Everything lives in `index.html`. To change the date, name, message, or bpm, edit the values at the top of the `<script>` block and the text in `<header>`.
