# 36c3 Generator
Generative Artwork for 36th Chaos Communication Congress  
Generative Artwork for 36th Chaos Communication Congress  
Generative Artwork for 36th Chaos Communication Congress  


[Original live version](https://36c3.bleeptrack.de)  
[Live version with sound synthesis](https://quantenprojects.github.io/36c3-generator/)__
[Live version with adjustable frequency (WIP)](https://chuckthegecko.github.io/36c3-generator/)_

Change the framerate variable with Chrome Dev Tools: Sources -> generator.js -> search: const framerate.
Preview changes by setting an Overrides directory in the left sidebar's "Overrides" tab, and then choose "Save for overrides" via right click on the changed js file. The change becomes active on stop/restart of "Play Sound"

![generator screenshot](https://github.com/bleeptrack/36c3-generator/blob/master/img/screenshot.png)

# TODO: (Gecko)
[ ] integrate `framerate` variable into the user interface
    - make all dependent variables not const for live change, or enable change only when audio is not playing, then reinitialize on restart
    
# Roadmap (Gecko)
[ ] evaluate if resonance driving can be used (probably only for rastering, not these vectors)
[ ] integrate resonance/harmonics finder to quickly calibrate the framerate to the resonance

# Uses:
[Font: Blackout](https://github.com/theleagueof/blackout)  
[Physic Engine: matter.js](https://brm.io/matter-js/)  
[Polygon Decomposing: decomp.js](https://github.com/schteppe/poly-decomp.js/)  
[Font Rendering: opentype.js](https://github.com/opentypejs/opentype.js/blob/master/README.md)  
[SVG Generation: paper.js](http://paperjs.org/)

