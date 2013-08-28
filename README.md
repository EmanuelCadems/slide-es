Remote Presentation Controller
==============================

This is an copy from remote presentation controller.

This is a slide about elasticsearch with rails4 and tire.


## Install

1) Install node.js

2) Run

node app.js

3) Preloaded with 2 sample presentations:

- [http://localhost:3000/demo](http://localhost:3000/demo) : Demo presentation from <http://lab.hakim.se/reveal-js>
- <http://localhost:3000/myppt>

Open another browser window to open the remote controller:

<http://localhost:3000/controller>

Users can issue up, down, left, right commands to navigate through the slides.

To remote control, just use the dropdown to select which presentation to control, then select one of the slides.


## Note

- config/index.js: configure the list of presentations and its initial slides
- routes/index.js: server logic
- views/controller.ejs: controller client logic
- views/layout.ejs: most of the logic for a normal presentations
- views/demo.ejs: actual html for 'Demo Presentation'
- views/myppt.ejs: html for 'My Presentation'



