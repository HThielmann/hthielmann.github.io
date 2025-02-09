---
title: Methodenradar
subtitle: Übersicht über alle Methoden
permalink: /methods/
hero-height: is-low
show_sidebar: false
---
<script src="https://d3js.org/d3.v4.min.js"></script>
<script src="../assets/js/radar.js"></script>

<svg class="radar" id="radar"></svg>

<script>
radar_visualization({
  svg_id: "radar",
  width: 1450,
  height: 1000,
  colors: {
    background: "#fff",
    grid: "#bbb",
    inactive: "#ddd"
  },
  quadrants: [
    { name: "Deliver" }, //0
    { name: "Develop" }, //1
    { name: "Discover" },//2
    { name: "Define" }   //3
  ],
  rings: [
    { name: "Entscheidungsmacht", color: "#93c47d" },       //0
    { name: "teilw. Entscheidungsmacht", color: "#93d2c2" },//1
    { name: "Mitbestimmung", color: "#fbdb84" },            //2
    { name: "Einbeziehung", color: "#efafa9" },             //3
    { name: "Anhörung", color: "#857dc4" },                 //4
    { name: "Information", color: "#efafa9" },              //5
    { name: "nicht beteiligt", color: "#efafa9" }           //6
  ],  
  /*
   color_code
   - Established Method #93c47d
   - New developed Method #93d2c2
   - Method to be tested #fbdb84
   - other #efafa9
  */
  print_layout: false,
  //zoomed_quadrant: 0,
  //ENTRIES
  entries: [
      {
        quadrant: 2,
        ring: 5,
        label: "Hospitation",
        active: true,
        link: "hospitation",
        moved: 0,
        color_code: "#93c47d"
      },
      {
        quadrant: 1,
        ring: 3,
        label: "Workshops",
        active: true,
        link: "workshop",
        moved: 10,
        color_code: "#93c47d"
      },
      {
        quadrant: 2,
        ring: 4,
        label: "Escape Game",
        active: true,
        link: "escape-game",
        moved: 0,
        color_code: "#93d2c2"
      },
      
      {
        quadrant: 2,
        ring: 5,
        label: "Check-In",
        active: true,
        link:  "check-in",
        moved: 0,
        color_code: "#93c47d"
      },
      {
        quadrant: 2,
        ring: 5,
        label: "Warm-Ups",
        active: true,
        link:  "warm-ups",
        moved: 0,
        color_code: "#93c47d"
      },
      {
        quadrant: 2,
        ring: 3,
        label: "Smiley Feedback",
        active: true,
        link:  "smiley-feedback",
        moved: 0,
        color_code: "#93c47d"
      },
      {
        quadrant: 2,
        ring: 3,
        label: "Erfindungsmemory",
        active: true,
        link:  "memory",
        moved: 0,
        color_code: "#93c47d"
      },
      {
        quadrant: 2,
        ring: 3,
        label: "Erfindungsskala",
        active: true,
        link:  "inventor-scale",
        moved: 0,
        color_code: "#93c47d"
      },
      {
        quadrant: 2,
        ring: 4,
        label: "Interviews",
        active: true,
        link:  "interviews",
        moved: 0,
        color_code: "#93c47d"
      },
      {
        quadrant: 2,
        ring: 4,
        label: "„Stimmt oder Stimmt Nicht“",
        active: true,
        link:  "true-or-not",
        moved: 0,
        color_code: "#93c47d"
      },
      {
        quadrant: 2,
        ring: 3,
        label: "Der Superheld",
        active: true,
        link:  "super-hero",
        moved: 0,
        color_code: "#93c47d"
      },
      {
        quadrant: 1,
        ring: 2,
        label: "Paper Function Mapping",
        active: true,
        link:  "pfm",
        moved: 0,
        color_code: "#93d2c2"
      },
      {
        quadrant: 1,
        ring: 2,
        label: "Behaviour-Driven Prototyping",
        active: true,
        link:  "bdp",
        moved: 0,
        color_code: "#93d2c2"
      },
      {
        quadrant: 1,
        ring: 4,
        label: "Probe Kit",
        active: true,
        link: "probe-kit",
        moved: 0,
        color_code: "#93d2c2"
      },
  ]
  //ENTRIES
});
</script>

<table>
<tr>
<td>

<h3>Was ist das Methoden Radar?</h3>

<p>
Das INTIA Methoden Radar ist eine Liste von methoden, die nach dem Einsatz im Projekt basierend auf ihrem Partizipationsgrad eingeordnet wurden:
</p>
<ul>
<li><strong>Entscheidungsmacht</strong> &mdash; TBD</li>
<li><strong>teilw. Entscheidungsmacht</strong> &mdash; TBD</li>
<li><strong>Mitbestimmung</strong> &mdash; TBD</li>
<li><strong>Einbeziehung</strong> &mdash; TBD</li>
<li><strong>Anhörung</strong> &mdash; TBD</li>
<li><strong>Information</strong> &mdash; TBD</li>
<li><strong>nicht beteiligt</strong> &mdash; TBD</li>
</ul>

</td><td>

<h3>Was ist der Zweck des ganzen?</h3>

<p>
TBD
</p>
</td></tr>
</table>