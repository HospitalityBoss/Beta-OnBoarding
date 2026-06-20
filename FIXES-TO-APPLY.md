# Two Surgical Fixes — Fast Casual Module

You already have hospitality_boss_fast_casual.html. Apply these two small edits,
then drop it in the beta folder as `fast-casual.html`.

## Fix 1 — Rendering bug (3 PM bar, double style attribute)

FIND:
    <div class="tx-bar" style="height:15px;background:var(--tomato)" style="opacity:0.6"></div>

REPLACE WITH:
    <div class="tx-bar" style="height:15px;background:var(--tomato);opacity:0.6"></div>

(The browser ignores the second style attribute, so the opacity never applies.
Merging them into one style fixes it.)

## Fix 2 — Add the demo banner

FIND:
    <div class="app">

    <!-- ── SIDENAV ── -->

REPLACE WITH:
    <div class="demo-banner">◆ Interactive Demo · Sample Data · Cedar &amp; Vine Catering (fictional)</div>
    <div class="app">

    <!-- ── SIDENAV ── -->

Then add this CSS rule inside the <style> block (anywhere):

    .demo-banner{background:rgba(184,115,51,0.1);border-bottom:1px solid rgba(184,115,51,0.25);text-align:center;padding:6px;font-size:10px;letter-spacing:2px;text-transform:uppercase;color:var(--copper-dark);}

That's it. The file is otherwise already in the correct light-mode brand system —
parchment workspace, dark Cast Iron nav rail, copper accents, food signal colors.
No real data to scrub (generic menu items, no names, no WCH entities).
