<h1> Coding Challenge </h1>

<h2> Challenges </h2>
<ol>
<li>Writing DRY html/css - a lot of this layout was "mirrored" - the same pieces were repeated but with different positions. It was challenging to know how to divy up the html, and i feel like i have some useless classes that were only used for styling purposes</li>
<li>Adding in the orange horizontal lines and adding the orange border to the featured-events div. Lines are hard! </li>
<li>Deciding how to position the centered 'featured-events' img - ended up positioning it absolute on-top of all other items </li>
</ol>

<h2> Outstanding Issues </h2>
<ol>
<li> Had to use a hacky way to calculate sizes - used my on-screen ruler to calculate the size of my #main-container and #sub-container and then every other size/padding/dimension was based off of that. Not ideal.</li>
<li> The horizontal lines underneath the event types are not working. Refactored a few times to try and come up with better solution (including creating them as empty divs with just a border-top). Right now they get out of place on window re-size so the CSS is commented out. Tried different positionings (wanted to have then absolute and inline-block but the window resizing messed this up - not sure why)</li>
</ol>
