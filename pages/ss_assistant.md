---
layout: singlepage
title: Signal Strength Assistant
permalink: /ss_assistant/
---

<script>
function toggleSection(sectionId) {
  var section = document.getElementById(sectionId);
  if (section.style.display === "none") {
    section.style.display = "block";
  } else {
    section.style.display = "none";
  }
}

function toggleSections(buttonId, prefix, startIndex, endIndex) {
    var categoryButton = document.getElementById(buttonId);
    var show = categoryButton.textContent == "Show"
    if (show) {
        categoryButton.textContent = "Hide";
    } else {
        categoryButton.textContent = "Show";
    }

    for (var i = startIndex; i <= endIndex; i++) {
        var section = document.getElementById(prefix + i);
        var sectionButton = document.getElementById(prefix+'b'+i);
        if (show) {
            sectionButton.style.display = "block";
            section.style.display = "none";
        } else {
            sectionButton.style.display = "none";
            section.style.display = "none";
        }
    }
}
</script>

<!-- Wifi button -->
<div style="display: inline-block; vertical-align: middle;">
  <h2 style="display: inline-block; vertical-align: middle; margin-right: 10px;">Wifi Problems</h2>
  <a href="#" id="toggleWifi" onclick="toggleSections('toggleWifi','w',1,4)" style="display: inline-block; vertical-align: top; padding: 8px 16px; ">Show</a>
</div>


<button id="wb1" style="display: none;" onclick="toggleSection('w1')">1. Low Signal</button>
<section id="w1" style="display: none;">
  <p>This is the content of Section 1.</p>
</section>
<button id="wb2" style="display: none;" onclick="toggleSection('w2')">2. Low Speed</button>
<section id="w2" style="display: none;">
  <p>This is the content of Section 1.</p>
</section>
<button id="wb3" style="display: none;" onclick="toggleSection('w3')">3. Connectivity</button>
<section id="w3" style="display: none;">
  <p>This is the content of Section 1.</p>
</section>
<button id="wb4" style="display: none;" onclick="toggleSection('w4')">4. Connectivity</button>
<section id="w4" style="display: none;">
  <p>This is the content of Section 1.</p>
</section>

## Cellular problems

<button onclick="toggleSection('c1')">1. No 5G</button>

<section id="c1" style="display: none;">
  <p>5G is mostly rolling out in an incremental (NSA - Non stand alone) approach utilizing the existing 4G networks.
In this hybrid approach the devices have dual connectivity to both 4G and 5G networks.
4G is primary and 5G is secondary network.
When secondary is in range device is connected to both 4G and 5G simultaneously.
However since this is rolling out stage number of 5G cells will be limited.
So 5G connectivity may not be there all the time even though your network is NSA.
This app will report 5G only if 5G cells are in range.
This will most probably be at variance with device status bar which will report 5G if NSA is detected.
Please help to improve app by giving feedback on this issue.</p>
</section>

<button onclick="toggleSection('section2')">Toggle Section 2</button>

<section id="section2" style="display: none;">
  <h2>Section 2</h2>
  <p>This is the content of Section 2.</p>
</section>
