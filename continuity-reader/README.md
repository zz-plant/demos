# Continuity Reader

Open `index.html` in a browser. Type into the notes textarea and resize between narrow and wide layouts. The same DOM textarea survives, so text, focus, and selection are not lost through responsive reflow. Segment-specific CSS is a progressive enhancement.

This demonstrates a deliberately limited property: continuity from **CSS reflow without DOM replacement**. It does not simulate folding hardware, persist drafts across page reloads, or claim that framework component remounts preserve state.

Test manually on an ordinary phone, wide viewport, and supported foldable browsers. Confirm keyboard, screen reader ordering, and reduced-motion settings as appropriate.
