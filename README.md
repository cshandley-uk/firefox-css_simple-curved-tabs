# firefox-css_simple-curved-tabs
Firefox chrome CSS to add simple (slightly Australis-like) curved tabs.

The CSS is kept as simple as possible (even if the result isn't artistically perfect), so that a FF update is less likely to break it & so that it will be easier to fix when it does break.  

I created this after github.com/wilfredwee/photon-australis was broken on Linux (only) by a FF update, which the author seemingly has no interest in fixing, and no-one else (me included) had any clue how to fix as the CSS is far too long & complicated.  
I did discover github.com/QNetITQ/WaveFox as a possible alternative, but it's even more complex, and I don't like that it requires many SVG files (which could potentially be a security risk).

I'm welcome to receiving improvements to the CSS that make it look better, but I'll only accept them if they don't make the CSS drastically more complex.

The simplicity of the CSS likely makes this a good starting point for developing your own (more complex) curved tabs implementation.

## Installation
Copy `chrome/userChrome.css` into your Firefox profile folder:
* Start Firefox.
* Open the address `about:profiles` .
* If there is more than one profile then use the one labelled as `This is the profile in use`.
* Click the "Open Directory" button next to Root Directory path.
* Create a `chrome` folder & then inside it save the `userChrome.css` file.
* Restart Firefox.

## If doesn't work
* Open the address `about:config` .
* Search for `toolkit.legacyUserProfileCustomizations.stylesheets` (and create it as a **Boolean** if it doesn't exist).
* Set it to **true**.
* Restart Firefox.
